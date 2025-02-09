
# RPM Reborn


## Configuration
Refer to the config files comments to configure the macro to your desires.

For maximum integration with Happy Hare, make use of the [gcode pre-processing](https://github.com/moggieuk/Happy-Hare/wiki/Gcode-Preprocessing). Make sure to include `PURGE_VOLUMES=!purge_volumes!`

Add RPMR to the post_load sequence in mmu_macro_vars.cfg
`variable_user_post_load_extension   : "RPMR"`

That's it. The RPMR will now automatically be called for a purge everytime you swap materials. Oh... don't forget to disable that filthy wipe tower.



Do you like this derivative of the Blobifier? Consider [buying dendrowen a coffee](https://www.buymeacoffee.com/dendrowen) or support him through [paypal](https://www.paypal.com/donate/?business=H88MZT7TGXNWJ&no_recurring=0&item_name=Support+my+work&currency_code=EUR)