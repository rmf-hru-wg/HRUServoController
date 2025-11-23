# HRU-SCB-uHAT


## Tri-State

3.3VレベルのUARTからシリアルサーボ向けの5V半二重シリアルに変換するICの選定。
SC16IS762を使用するので、同系列からNexperiaの74系ロジックICより2G241のシリーズを選択。
最終的にTTLサポートで主電源5V前後での使用を想定した汎用ICから、74AHCT2G241とした。
<https://assets.nexperia.com/documents/data-sheet/74AHC_AHCT2G241.pdf>

なお74系はLVCやAHC/Tなどいくつかのシリーズがあるが、NexperiaのLogic Application Handbookにある"Table 6: Picogate portfolio Parametrics and features"などがわかりやすい。
<https://www.nexperia.com/dam/jcr:851f7c27-b0e9-4627-84b9-13b132388708/Nexperia_LOGIC_Handbook.pdf>

## Reference

- Raspberry Pi HAT Specification: https://github.com/raspberrypi/hats
- SC16IS752 Linux Driver: https://github.com/raspberrypi/linux/issues/3231