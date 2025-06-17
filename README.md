# CyberArk-Nutanix-Prism

Update Nutanix Prism IAM Identities via WSChains

Entirely not possible without the guidance of [aaearon](https://github.com/aaearon) with his [blog on WSChains](https://timschindler.blog/creating-a-cyberark-central-policy-manager-plugin-for-an-api-using-wschains). Thank you!

This relies on the v4 IAM API, which requires [pc.2024.3 or later and AOS 7.0](https://www.nutanix.dev/api-reference-v4/#:~:text=Identity%20and%20Access,7.0).

## Installation

1. Download the latest release and inject `Cyberark.Extensions.Plugin.WSChains.dll` into the downloaded `.zip`. Speak with your account team to obtatin it.
1. Upload the `.zip` to CPM.
