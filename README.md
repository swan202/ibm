# IBM Cloud Foundry - V2Ray

Use GitHub Actions to automatically deploy the latest version of V2Ray to IBM Cloud Foundry

## Usage

- Click the [Use this template](https://github.com/P3TERX/IBM-CF-V2/generate) button to create a new repository.
- Click the `Settings` tab on your own repository, and then click the `Secrets` button to add the following encrypted environment variables:
  - `IBM_CF_USERNAME`: IBM Cloud user name (email address)
  - `IBM_CF_PASSWORD`: IBM Cloud password
  - `IBM_CF_ORG_NAME`: Organization name, the default is the email address. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry).
  - `IBM_CF_SPACE_NAME`: Space name, default is `dev`. Can be found on [this page](https://cloud.ibm.com/account/cloud-foundry).
  - `IBM_CF_APP_NAME`: App name, fill in according to your preference.
  - `V2_UUID`: UUID generator
  - `V2_WS_PATH`: Any combination of English letters and numbers.
- Click the `Run workflow` button on the Actions page.
- Wait for the deployment to complete.
- Click the relevant application on the [Cloud Foundry Public](https://cloud.ibm.com/cloudfoundry/public) page to view the access address.

> **TIPS:** You can customize the API address and App memory size through the workflow file.

## Acknowledgments

- [Project V](https://github.com/v2ray)
- [IBM Cloud](https://cloud.ibm.com/)
- [GitHub Actions](https://github.com/features/actions)

## Licence

[MIT](https://github.com/P3TERX/IBM-CF-V2/blob/main/LICENSE) © P3TERX
