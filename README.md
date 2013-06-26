recovery_TWRP
=============



Team Win Recovery Project (TWRP)

The goal of this branch is to rebase TWRP onto AOSP while maintaining as much of the original AOSP code as possible. This goal should allow us to apply updates to the AOSP code going forward with little to no extra work. With this goal in mind, we will carefully consider any changes needed to the AOSP code before allowing them. In most cases, instead of changing the AOSP code, we'll create our own functions instead. The only changes that should be made to AOSP code should be those affecting startup of the recovery and some of the make files.

If there are changes that need to be merged from AOSP, we will pull the change directly from AOSP instead of creating a new patch in order to prevent merge conflicts with AOSP.

This branch is under final testing and will be used shortly for public builds, but has not officially been released.

You can find a compiling guide here.

More information about the project.

If you have code changes to submit those should be pushed to our gerrit instance. A guide can be found here.

