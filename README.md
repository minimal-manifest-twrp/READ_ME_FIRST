## TWRP Minimal Manifests ##
------------------
There are manifests to build with the AOSP 11 branch, OmniROM 5.1-10 branches, and LineageOS 14.1 branch. As new Android versions are released, it becomes more and more difficult to maintain these minimal manifests, so pull requests are welcome!

Note that each branch has its own README file which may include specific details about how to build on that branch. For example, starting with the 8.1 OmniROM branch, adding the command "export ALLOW_MISSING_DEPENDENCIES=true" to the command line is necessary to ensure a proper compile when using the minimal manifest. **Please make sure you read these files to be aware of such notes!**

If you find that any changes are needed, such as additional packages for required builds that need to be added, please submit a pull request for review. In some cases, it may make more sense to use a local manifest to pull device-specific packages.
