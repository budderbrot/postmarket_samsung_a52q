# postmarket_samsung_a52q
postmarketOS for Samsung Galaxy A52

## Works
- USB Gadget mode
- Display (samsung,s6e3fc3-ams667ym01)
- GPU (FD618)
- Audio (only built in stereo speakers)
- Modem (works only with modemmanager. ofone doesn't seem to work)
- Wifi
- Bluetooth
- CPU (tlmm, clock controllers)
- UFS Storage
- SDHC (SDCard)
- IOMMU
- Battery (sm5714-fg)
- Charger (sm5714-charger)
- Touchscreen (stmfts_fts5cu56a)
- Venus (hardware video decoding/encoding)
- Some other things from sc7180.dtsi
## Broken
- Accelerometer & Gyroscope (lsm6dso)
## Bugs
- Display Brightness(Changing brightness causes artifacts)
- Modem sometimes can't start at boot.
