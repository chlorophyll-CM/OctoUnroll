# OctoUnroll
Unenrollment method for Octopus boards with SH1MMERS CSS/HTMl/JS
This method involes a set of TPM commands that removes Organization ownership
This method wont work in the future because google is geting rid of Disabling WP
So hopefully in them doing this they will just add an extra step to doing so
SO shim up and TPM down -Phill

Here is proof of them getting rid of the ability to Disable WP

https://source.chromium.org/chromiumos/chromiumos/codesearch/+/main:src/platform/cr50/board/cr50/wp.c;l=101

Im pretty sure the only way to fix this is to delete the lines and of code and compile chromiumos turn it into chromeos with what CoolElectronics said And install ARCVM or ARC++ but then again im not sure that will work because chromeos is secure and not secure at the same time And without disabling wp i cant get fast boot screens for dev mode :(

Or back up your chromebook and flash it to your cr50/EMMC i dont really know if thats how because ive never used a bus pirate before
