installdir = $(pkglibdir)/python/Plugins/SystemPlugins

SUBDIRS = SoftwareManager PositionerSetup Satfinder \
	VideoTune Hotplug \
	DefaultServicesScanner CommonInterfaceAssignment \
	HdmiCEC VideoClippingSetup \
	VideoEnhancement WirelessLan NetworkWizard \
	SABnzbdSetup OSD3DSetup DeviceManager SwapManager LCNScanner

if XTREND
SUBDIRS += SatelliteEquipmentControl DiseqcTester
endif

if ODIN
SUBDIRS += SatelliteEquipmentControl DiseqcTester
endif

if VUSOLO2
SUBDIRS += SatelliteEquipmentControl DiseqcTester
endif

if VUUNO
SUBDIRS += SatelliteEquipmentControl DiseqcTester CableScan
endif

if VUULTIMO
SUBDIRS += SatelliteEquipmentControl DiseqcTester CableScan
endif

if DREAMBOX
SUBDIRS += FrontprocessorUpgrade NFIFlash SatelliteEquipmentControl DiseqcTester CableScan
endif

install_PYTHON =	\
	__init__.py
