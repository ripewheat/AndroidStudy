Simply change ro to rw and add the remount option
# mount -o rw,remount /system

Once you are done making changes, you should remount with the original readonly.
# mount -o ro,remount /system