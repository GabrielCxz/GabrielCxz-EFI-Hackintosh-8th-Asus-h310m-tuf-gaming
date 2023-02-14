EFI-Hackintosh-8th-Asus-h310m-t# EFI-Hackintosh-8th-Asus-h310m-tuf-gaming

	º Opencore 0.8.9
	º Ventura
	
<img width="300" height="300" src="Sobre este Mac.png">

Meu pc

	º Asus h310m tuf gaming
	º i5 8400t
	º Rx 570 4Gb Sapphire
	º 8Gb Ddr4

Funcionando 

	º Aceleração Gráfica
	º Rede
	º Som
	º Sleep
	º Virtualização 
	º Bluetooth (Orico USB)

Não Funciona

	º Quick Sync 

SMBIOS (IMPORTANTE !)

	º Atualizar os parâmetros em "PlatformInfo" > "Generic" para iMacPro1,1 usando GenSMBIOS
Kexts

	º AppleAlc (Corrige o Áudio)
	º AppleMCEReporterDisabler (desativa o AppleIntelMCEReporter)
	º BlueToolFixup.kext (Corrige o bluetooth usb)
	º IntelMausi (Corrige a rede para placas Intel's 82578, 82579, I217, I218 and I219)
	º Lilu (Corrige muitos processos, necessária para AppleALC, WhateverGreen, VirtualSMC e outras kexts)
	º RestrictEvents (Extensão Lilu)
	º SMCProcessor (Usado para monitorar a temperatura da CPU)
	º USBInjectAll (Usado para injetar controladores Intel USB em sistemas sem portas USB definidas em ACPI)
	º VirtualSMC (Emula o chip SMC encontrado em macs reais, sem este macOS não inicializa)
	º WhateverGreen (Usado para correção de gráficos, correções de DRM, verificações de ID de placa, correções de framebuffer, etc)
	º XHCI-unsupported (Necessário para controladores USB não nativos)

ACPI Tables 

	º SSDT-AWAC-DISABLE
	º SSDT-EC-USBX
	º SSDT-PLUG
	º SSDT-PMC
	º SSDT-SBUS-MCHC

Configurações na BIOS

º Desativado

  	º Fast Boot
	º Secure Boot
	º VT-D
º Ativado

  	º Intel Virtualization

