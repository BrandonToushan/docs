# Install KoBoToolbox on Your Own Servers

**Warning: Installing KoBoToolbox on your own server requires advanced server administration and programming skills. Please understand that you shouldn't use this in a critical environment without having the technical resources in place to troubleshoot if needed. Consider installing KoBo on your local computer instead with [these instructions](kobo_local_computer.html).**

All of the components of KoBoToolbox can be installed on your own servers. KoBoToolbox is free and open source, and our code can be found on [GitHub](https://github.com/kobotoolbox).
 
We have created a simplified process using Docker called kobo-install, which can be found [here](https://github.com/kobotoolbox/kobo-install). This is currently only supported on Linux machines (we recommend Ubuntu Server 18.04.3 LTS or similar with at least 4GB RAM and at least 20GB storage). We recommend installing the software first on a local machine using the same script since server installations require additional configurations for domain names and SSL certificates.

For details about the different components making up KoBoToolbox, see [this post](software_architecture.html).

