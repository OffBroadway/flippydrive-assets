# flippydrive-assets

The latest FlippyDrive software can be [accessed in the releases](https://github.com/OffBroadway/flippydrive-assets/releases)

Place the `update.fpkg` on your sd card and hold `X` during boot to trigger an update.  The file will be removed automatically upon completion.

`recovery.uf2` is a special brick recovery program in case the standard update process fails for some reason.  Power off your cube, hold the button on the FlippyDrive while attaching it to USB and continue to hold until it mounts as a USB Mass Storage Device.  Copy the recovery file to the root of the drive.  It will unmount and reboot automatically.  On the next cube bootup, the update will self-extract and install automatically.
