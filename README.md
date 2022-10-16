# balena-firefly

[Firefly III](https://www.firefly-iii.org/) is a (self-hosted) manager for your personal finances. It can help you keep track of your expenses and income, so you can spend less and save more.

## Getting Started

You can one-click-deploy this project to balena using the button below:

[![deploy-with-balena](https://balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/moe-sani/balena_firefly&defaultDeviceType=raspberrypi4-64)

## Manual Deployment

Alternatively, deployment can be carried out by manually creating a [balenaCloud account](https://dashboard.balena-cloud.com) and application, flashing a device, downloading the project and pushing it via the [balena CLI](https://github.com/balena-io/balena-cli).

### Application Environment Variables

Please refer to [Firefly III documentatio](https://docs.firefly-iii.org/firefly-iii/installation/docker/?mtm_campaign=docu-internal&mtm_kwd=docker)

## Usage

Once your device joins the fleet you'll need to allow some time for it to download the various services.

When it's done you should be able to access the access the dashboard at <http://<IP ADDRESS>>.


## Contributing

Please open an issue or submit a pull request with any features, fixes, or changes.