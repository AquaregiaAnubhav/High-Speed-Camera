# Info about camera being used.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

P: /devices/pci0000:00/0000:00:14.0/usb1/1-3/1-3.3
N: bus/usb/001/007
L: 0
E: DEVPATH=/devices/pci0000:00/0000:00:14.0/usb1/1-3/1-3.3
E: DEVNAME=/dev/bus/usb/001/007
E: DEVTYPE=usb_device
E: DRIVER=usb
E: PRODUCT=bda/5842/1
E: TYPE=239/2/1
E: BUSNUM=001
E: DEVNUM=007
E: MAJOR=189
E: MINOR=6
E: SUBSYSTEM=usb
E: USEC_INITIALIZED=1043413287
E: ID_VENDOR=Generic
E: ID_VENDOR_ENC=Generic
E: ID_VENDOR_ID=0bda
E: ID_MODEL=USB_Camera
E: ID_MODEL_ENC=USB\x20Camera
E: ID_MODEL_ID=5842
E: ID_REVISION=0001
E: ID_SERIAL=Generic_USB_Camera_200901010001
E: ID_SERIAL_SHORT=200901010001
E: ID_BUS=usb
E: ID_USB_INTERFACES=:0e0100:0e0200:010100:010200:
E: ID_VENDOR_FROM_DATABASE=Realtek Semiconductor Corp.
E: ID_PATH=pci-0000:00:14.0-usb-0:3.3
E: ID_PATH_TAG=pci-0000_00_14_0-usb-0_3_3

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## dev/video2 info:
-----------------------------------------------------------------------------------------------------------------------------------------------------------

*Driver Info:*
	Driver name      : uvcvideo
	Card type        : USB Camera: USB Camera
	Bus info         : usb-0000:00:14.0-3.3
	Driver version   : 6.5.13
	Capabilities     : 0x84a00001
		Video Capture
		Metadata Capture
		Streaming
		Extended Pix Format
		Device Capabilities
	Device Caps      : 0x04200001
		Video Capture
		Streaming
		Extended Pix Format
*Media Driver Info:*
	Driver name      : uvcvideo
	Model            : USB Camera: USB Camera
	Serial           : 200901010001
	Bus info         : usb-0000:00:14.0-3.3
	Media version    : 6.5.13
	Hardware revision: 0x00000001 (1)
	Driver version   : 6.5.13
*Interface Info:*
	ID               : 0x03000002
	Type             : V4L Video
*Entity Info:*
	ID               : 0x00000001 (1)
	Name             : USB Camera: USB Camera
	Function         : V4L2 I/O
	Flags            : default
	Pad 0x01000007   : 0: Sink
	  Link 0x02000013: from remote pad 0x100000a of entity 'Extension 6' (Video Pixel Formatter): Data, Enabled, Immutable
Priority: 2
Video input : 0 (Camera 1: ok)
*Format Video Capture:*
	Width/Height      : 1920/1080
	Pixel Format      : 'MJPG' (Motion-JPEG)
	Field             : None
	Bytes per Line    : 0
	Size Image        : 4147200
	Colorspace        : sRGB
	Transfer Function : Rec. 709
	YCbCr/HSV Encoding: ITU-R 601
	Quantization      : Default (maps to Full Range)
	Flags             : 
*Crop Capability Video Capture:*
	Bounds      : Left 0, Top 0, Width 1920, Height 1080
	Default     : Left 0, Top 0, Width 1920, Height 1080
	Pixel Aspect: 1/1
Selection Video Capture: crop_default, Left 0, Top 0, Width 1920, Height 1080, Flags: 
Selection Video Capture: crop_bounds, Left 0, Top 0, Width 1920, Height 1080, Flags: 
Streaming Parameters Video Capture:
	Capabilities     : timeperframe
	Frames per second: 30.000 (30/1)
	Read buffers     : 0

### User Controls

                     brightness 0x00980900 (int)    : min=-64 max=64 step=1 default=0 value=0
                       contrast 0x00980901 (int)    : min=0 max=100 step=1 default=50 value=50
                     saturation 0x00980902 (int)    : min=0 max=100 step=1 default=65 value=65
                            hue 0x00980903 (int)    : min=-180 max=180 step=1 default=0 value=0
        white_balance_automatic 0x0098090c (bool)   : default=1 value=1
                          gamma 0x00980910 (int)    : min=100 max=500 step=1 default=300 value=300
           power_line_frequency 0x00980918 (menu)   : min=0 max=2 default=1 value=1 (50 Hz)
				0: Disabled
				1: 50 Hz
				2: 60 Hz
      white_balance_temperature 0x0098091a (int)    : min=2800 max=6500 step=10 default=4600 value=4600 flags=inactive
                      sharpness 0x0098091b (int)    : min=0 max=100 step=1 default=50 value=50
         backlight_compensation 0x0098091c (int)    : min=0 max=2 step=1 default=0 value=0

### Camera Controls

                  auto_exposure 0x009a0901 (menu)   : min=0 max=3 default=3 value=3 (Aperture Priority Mode)
				1: Manual Mode
				3: Aperture Priority Mode
         exposure_time_absolute 0x009a0902 (int)    : min=50 max=10000 step=1 default=166 value=166 flags=inactive
     exposure_dynamic_framerate 0x009a0903 (bool)   : default=0 value=1
                   pan_absolute 0x009a0908 (int)    : min=-57600 max=57600 step=3600 default=0 value=0
                  tilt_absolute 0x009a0909 (int)    : min=-43200 max=43200 step=3600 default=0 value=0
                 focus_absolute 0x009a090a (int)    : min=0 max=1023 step=1 default=68 value=68 flags=inactive
     focus_automatic_continuous 0x009a090c (bool)   : default=1 value=1
                  zoom_absolute 0x009a090d (int)    : min=0 max=3 step=1 default=0 value=0

------------------------------------------------------------------------------------------------------------------------------------------------------------
## dev/video3 info :
------------------------------------------------------------------------------------------------------------------------------------------------------------

*Driver Info:*
	Driver name      : uvcvideo
	Card type        : USB Camera: USB Camera
	Bus info         : usb-0000:00:14.0-3.3
	Driver version   : 6.5.13
	Capabilities     : 0x84a00001
		Video Capture
		Metadata Capture
		Streaming
		Extended Pix Format
		Device Capabilities
	Device Caps      : 0x04a00000
		Metadata Capture
		Streaming
		Extended Pix Format
*Media Driver Info:*
	Driver name      : uvcvideo
	Model            : USB Camera: USB Camera
	Serial           : 200901010001
	Bus info         : usb-0000:00:14.0-3.3
	Media version    : 6.5.13
	Hardware revision: 0x00000001 (1)
	Driver version   : 6.5.13
*Interface Info:*
	ID               : 0x03000005
	Type             : V4L Video
*Entity Info:*
	ID               : 0x00000004 (4)
	Name             : USB Camera: USB Camera
	Function         : V4L2 I/O
Priority: 2
*Format Metadata Capture:*
	Sample Format   : 'UVCH' (UVC Payload Header Metadata)
	Buffer Size     : 10240
-------------------------------------------------------------------------------------------------------------------------------------------------------------


