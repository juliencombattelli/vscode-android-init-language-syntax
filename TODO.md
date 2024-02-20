# To Do

- [x] Handle line continuation with backslash (cf. system/etc/init/init-debug.rc)
- [ ] Add shell syntax highlight for service commands
- [ ] Colorize property expansion differently that the rest of the commands/options value and in imports
      (for imports cf. system/system_ext/etc/init/init.gsi.rc)
- [ ] Colorize : and . as operators everywhere
- [ ] Do not colorize numbers inside strings in commands/options value
- [ ] Maybe handle all lines (after on as commands | after service as option) until next block
      => Allow to avoid listing all supported commands/options for a better maintainability
- [x] Handle multiline strings correctly (cf. system/etc/init/logd.rc)
- [x] Handle comments in commands/options lines correctly (cf. system/etc/init/odsign.rc)
- [ ] Colorize minus operator correctly in numbers (cf. system/etc/init/update_verifier.rc)
- [ ] Colorize , as operator in reboot_on_failure option (cf. system/etc/init/vold.rc)
- [ ] Colorize ueventd.rc which has a different syntax that other rc files
