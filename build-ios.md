1. Build cho device (arm64):
```bash
make -f makefile-iOS.gcc device
```
2. Build cho simulator (arm64):
```bash
make -f makefile-iOS.gcc simulator
```
3. Build cả hai:
```bash
make -f makefile-iOS.gcc all
```
4. Tạo XCFramework (Khuyến nghị):
```bash
make -f makefile-iOS.gcc xcframework
```