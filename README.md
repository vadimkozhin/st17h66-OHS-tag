# OpenHaystack Firmware for st17h66

This is the bare minimum firmware example for BLE tags based on st17h66 SoC with [OpehnHaystack](https://github.com/seemoo-lab/openhaystack) support. 

❗This project is under development

The project based on example from Lenze SDK with minimal modifications that allow the BLE tag to be displayed on the map in [OpenHaystack OSX app](https://github.com/seemoo-lab/openhaystack/tree/main/OpenHaystack). The project uses Keil MDK and µVision IDE, which is MS Windows only. 

The goal of this project is to make the tools and basic code example to build custom firmwares for st17h66 based BLE tags using open source software.

The project contains:

- [x] Arm Compiler v5 project (win, need license)
- [x] Lense flash tool LeKit (win)
- [x] Lense SDK 3.1.1.2 with sample projects for st17h66 (win)

##### TODO:

- [ ] System independent flash tool
- [ ] Arm Compiler v6 project (Windows, free for non-commercial use)
- [ ] Arm GNU project
- [ ] Flash instructions (win)
