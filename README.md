# Adding dokeymap Support

Before proceeding, this requires some knowledge of Catalyst.

## Creating a LiveCD

**IMPORTANT** If you wish to use your own specs, make sure your dracut 
command-line args follow the ones I have in my spec files.

1. Add everything in `portage/` into the appropiate folders inportage confdir 
2. Make a stage1, I've added one to this repo for conveinience
3. Copy `90dokeymap` into the **stage1 chroot** at `/usr/lib/dracut/modules.d/`
4. Copy `lib/keymaps` into the **stage1 chroot** at `/lib` 
5. Proceed with making a stage2
