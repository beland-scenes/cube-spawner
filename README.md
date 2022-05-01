# Beland scene

This folder contains all the necessary files to launch a Beland scene.

## Try it out

**Install the CLI**

Download and install the Beland CLI by running the following command:

```bash
npm i -g beland
```

**Previewing the scene**

Open this folder on the command line, then run:

```
bld start
```

Any dependencies are installed and then the CLI opens the scene in a new browser tab.

## Deploy to Beland

If you own any parcels of land in Beland, or have permissions to deploy to someone else's, you can publish this project.

1. Make sure the scene parcels in `scene.json` match those you own or have permissions on.
2. Run `bld deploy` on the project folder
3. This will open a browser tab to confirm. Metamask will prompt you to sign.
   > Note: Make sure you are using the wallet that owns the parcels or has permissions.

## Resources

Learn more about how to build your own scenes in our [documentation](https://docs.beland.io/) site.

## Copyright info

This scene is protected with a standard Apache 2 licence. See the terms and conditions in the [LICENSE](/LICENSE) file.