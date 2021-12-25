# Introduction 
Open source project for technical profiles (SAML 2.0) integration with Government of Canada's GCCF service and SignIn Canada (coming soon)

# Getting Started
Simply download the technical profiles, change the variables in the XML file to reflect your environment specific details - variables are prefixed with $ since variables should be used regardless if you decide to leverage a release pipeline using PowerShell and Azure DevOps. The deployment powershell script is included in this repository. *THIS DOES NOT INCLUDE ICM CATE CERTIFCATES - YOU NEED TO GET THESE FROM SSC AS PART OF THE GCCF ONBOARDING*

# Build and Test
We recommend you use Azure DevOps, GITHUB or GITLAB to make deploy and make changes to technical profiles in B2C so that you can integrate automated tests to elimiinate / minimize mis-configurations associated with manually uploading tech profiles to b2c which can cause security issues.

# Contribute
All pull requests will be reviewed for approval
