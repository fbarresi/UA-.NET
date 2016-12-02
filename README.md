# OPC Foundation UA .NET - Prototyping Branch
## Overview
The OPC Foundation has formally released the Unified Architecture .NET Stack and Sample Code to the community.

Please review official site page (http://opcfoundation.github.io/UA-.NET/) for:
 * Overview
 * Licensing
 * Sample Applications overview
 * Building UA Client/Server Walkthrough
 * Compliance Testing

## Prototyping Branch 
This branch contains code which is used to validate new features added to OPC UA.

There are three projects:
 * AMQP - samples that implement the AMQP transport and AMQP pub-sub; 
 * WebSocket - samples that implemengt the WebSocket transport;
 * GDS/OAuth2 - a modified GDS which implements OAuth2 based user authorization.
 
The sub-folder readme's have more information.

## Contributing
We strongly encourage community participation and contribution to this project. First, please fork the repository and commit your changes there. Once happy with your changes you can generate a 'pull request'.

You must agree to the contributor license agreement before we can accept your changes. The CLA and "I AGREE" button is automatically displayed when you perform the pull request. You can preview CLA [here](https://opcfoundation.org/license/cla/ContributorLicenseAgreementv1.0.pdf).

OPC UA, empowering the Industrial Internet of Things (IIOT) and Industrie 4.0.

10748:error:140C5042:SSL routines:ssl_undefined_function:called a function you should not call:.\ssl\ssl_lib.c:2821: