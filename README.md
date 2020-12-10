# Checkmarx CxFlow Orb [![CircleCI Build Status](https://circleci.com/gh/checkmarx-ts/checkmarx-cxflow-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/checkmarx-ts/checkmarx-cxflow-orb) [![CircleCI Orb Version](https://img.shields.io/badge/endpoint.svg?url=https://badges.circleci.io/orb/checkmarx-ts/cxflow)](https://circleci.com/orbs/registry/orb/checkmarx-ts/cxflow) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/checkmarx-ts/checkmarx-cxflow-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

A CircleCI Orb to simplify Checkmarx Scanning of source code along with Result consumption leveraging Checkmarx CxFlow solution.


For full usage guidelines, see the [orb registry listing](https://circleci.com/orbs/registry/orb/checkmarx-ts/cxflow)

## Usage

Example use-cases are provided on the orb [registry page](https://circleci.com/orbs/registry/orb/checkmarx-ts/cxflow#usage-examples). Source for these examples can be found within the `src/examples` directory.

The below are the required environment variables for CircleCI projects to leverage this Orb.
 
### Checkmarx SAST   
    - CHECKMARX_URL: High level dns entry for the Checkmarx SAST Instance including protocol/port (i.e. https://cxsast.example.com)
    - CHECKMARX_USERNAME: Service Account within Checkmarx SAST that will be used for triggering scans and retrieving results
    - CHECKMARX_PASSWORD: Password of the Checkmarx SAST Service Account
    - CHECKMARX_CLIENT_SECRET: Client secret key associated with your Checkmarx SAST account

### Checkmarx AST
    - AST_CLIENT_ID: Service account Client ID for Checkmarx AST 
    - AST_CLIENT_SECRET: Client secret key associated with your Checkmarx AST account

### Checkmarx SCA
    - SCA_USERNAME: Service Account within Checkmarx SCA that will be used for triggering scans and retrieving results
    - SCA_PASSWORD: Password of the Checkmarx SCA Service Account
    - SCA_TENANT: Tenant information of the Checkmarx SCA account

### Checkmarx CxGo
    - CXGO_CLIENT_SECRET: Client secret key associated with your Checkmarx CxGo account

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/checkmarx-ts/cxflow) - The official registry page of this orb for all versions, executors, commands, and jobs described.  
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.  

### How To Contribute

We welcome [issues](https://github.com/checkmarx-ts/checkmarx-cxflow-orb/issues) to and [pull requests](https://github.com/checkmarx-ts/checkmarx-cxflow-orb/pulls) against this repository!


For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).
