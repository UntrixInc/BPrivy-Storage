BPrivy-Desktop
==============

Storage Service for Browser Apps. Project to be started soon.

A desktop storage service that will export a web interface (permission based) allowing javascript code running inside browsers to access files on the desktop. Will come with a file-finder/explorer, a synchronizable DB as well as encryption/decryption. All of the code is already available within a proprietary browser-plugin (for windows), but since browser-plugins will soon be depricated, this workaround is needed. All implementation will be in javascript over a suitable platform such as node-js for the desktop and phonegap for mobile (Phase 2).

The long-term vision (Web-Storage2) is to provide a private web-storage for end-users - distributed and replicated across the end-users' devices. This would be useful to store sensitive private information that one is not comfortable delegating to the cloud. Web-Storage2 will provide a storage/DB service that can be run as a cluster on all your personal devices (laptops, tablets, phones) and will replicate (peer-2-peer) your data across these devices so that your data is available on all devices at all times. The novelty here would be that it is 100% web-technology oriented and does not require a cloud-server to store the data.
