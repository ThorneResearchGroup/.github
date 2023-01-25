# TRG Public Repos

Welcome to the Thorne Research Group public code repository. Each repository is under HEAVY development and is not suitable for production use

The repositories here are the very same repositories we use in production, so if you're looking to set up your own local instance of any individual/combination of repositories, you will have everything you need.

## Overview

Each project created by TRG is broken down into four sections, where applicable:
1. The backend or API server and microservices
2. The schema or model used to ingest or egress an interchange format
3. The library containing the REST client and functions used in the backend
4. The user interface (webui, cli, tui)

With that in mind, the repositories are laid out to be one repository per section.

1. Backend-*
2. Schema-*
3. Library-*
4. WebUI-*, CLI-*, TUI-*

Where the * is the name of the project. Eg if the name of my project was BabyGalago, the backend repo would be called Backend-BabyGalago.

Each of the backends have Docker images generated for them, which can be found here: https://hub.docker.com/repositories/jthorne94

Each of the schemas are published as a GitHub package

Each of the libraries are published as a GitHub package. You can use the library for communicating with the backend, or you can import the library as a dependency and run the same functions that the backend runs.

## Quick links

### Microservices:

[AntiVirus](https://github.com/orgs/ThorneResearchGroup/repositories?q=AntiVirus&type=all&language=&sort=) - Send it a file, it will scan the file with several antivirus engines

[AudioCompressor](https://github.com/orgs/ThorneResearchGroup/repositories?q=AudioCompressor&type=all&language=&sort=) - Send it an audio file, and it will re-encode it

[AudioEditor](https://github.com/orgs/ThorneResearchGroup/repositories?q=AudioEditor&type=all&language=&sort=) - Send it a file to manipulate it (eg, crop from x to y)

[AudioFingerprinter](https://github.com/orgs/ThorneResearchGroup/repositories?q=AudioFingerprinter&type=all&language=&sort=) - Send it an audio file and receive a fingerprint

[AudioNormalizer](https://github.com/orgs/ThorneResearchGroup/repositories?q=AudioNormalizer&type=all&language=&sort=) - Normalizes audio volume of an audio file

[AudioQualityDetector](https://github.com/orgs/ThorneResearchGroup/repositories?q=AudioQualityDetector&type=all&language=&sort=) - Send it a file to see whether the bitrate of an audio file is truly what it claims to be

[AudioRecognition](https://github.com/orgs/ThorneResearchGroup/repositories?q=AudioRecognition&type=all&language=&sort=) - Send it an unknown audio file, and it will return you information about what the file is

[Authentication](https://github.com/orgs/ThorneResearchGroup/repositories?q=Authentication&type=all&language=&sort=) - Used to authenticate users using JWTs

[BitTorrent](https://github.com/orgs/ThorneResearchGroup/repositories?q=BitTorrent&type=all&language=&sort=) - Controls bittorrent clients to download files

[BookFormatConverter](https://github.com/orgs/ThorneResearchGroup/repositories?q=BookFormatConverter&type=all&language=&sort=) - Convert book files between formats

[Compressor](https://github.com/orgs/ThorneResearchGroup/repositories?q=Compressor&type=all&language=&sort=) - Send it a file, and it will return a compressed version of it

[DMCA](https://github.com/orgs/ThorneResearchGroup/repositories?q=DMCA&type=all&language=&sort=) - Send it a file to see whether it has an active copyright

[Downloader](https://github.com/orgs/ThorneResearchGroup/repositories?q=Downloader&type=all&language=&sort=) - Send it a URL, and it will send back the file

[Email](https://github.com/orgs/ThorneResearchGroup/repositories?q=Email&type=all&language=&sort=) - Used to send and receive emails

[Encryption](https://github.com/orgs/ThorneResearchGroup/repositories?q=Encryption&type=all&language=&sort=) - Send it a file, and it will send it back encrypted

[FaceDetection](https://github.com/orgs/ThorneResearchGroup/repositories?q=FaceDetection&type=all&language=&sort=) - Send it an image, and it will return JSON about where faces are in the image

[FaceRecognition](https://github.com/orgs/ThorneResearchGroup/repositories?q=FaceRecognition&type=all&language=&sort=) - Send it the JSON output of FaceDetection, and it will crop the face and figure out who it is

[FileArchiver](https://github.com/orgs/ThorneResearchGroup/repositories?q=FileArchiver&type=all&language=&sort=) - Send it a bunch of files, and it will return an archive with the files in it

[FileIdentifier](https://github.com/orgs/ThorneResearchGroup/repositories?q=FileIdentifier&type=all&language=&sort=) - Send it a file with an unknown extension, and it will tell you the type

[FormatConverter](https://github.com/orgs/ThorneResearchGroup/repositories?q=FormatConverter&type=all&language=&sort=) - Convert files between supported formats

[Hashing](https://github.com/orgs/ThorneResearchGroup/repositories?q=Hashing&type=all&language=&sort=) - Send it a file, and it will return the files hash

[HostScanner](https://github.com/orgs/ThorneResearchGroup/repositories?q=HostScanner&type=all&language=&sort=) - Send it an IP, and it will scan it

[ImageCompressor](https://github.com/orgs/ThorneResearchGroup/repositories?q=ImageCompressor&type=all&language=&sort=) - Send it an image, and it will compress it =

[ImageEditor](https://github.com/orgs/ThorneResearchGroup/repositories?q=ImageEditor&type=all&language=&sort=) - Send it a file, and it will manipulate it (Eg, crop from x to y)

[Invoicing](https://github.com/orgs/ThorneResearchGroup/repositories?q=Invoicing&type=all&language=&sort=) - Create invoices in QuickBooks

[IPFS](https://github.com/orgs/ThorneResearchGroup/repositories?q=IPFS&type=all&language=&sort=) - Control files in IPFS (desktop & swarm)

[LinkShortener](https://github.com/orgs/ThorneResearchGroup/repositories?q=LinkShortener&type=all&language=&sort=) - Create shorter links

[Logging](https://github.com/orgs/ThorneResearchGroup/repositories?q=Logging&type=all&language=&sort=) - Send it JSON, it will store it in Kafka and eventually append it to the log

[Morse](https://github.com/orgs/ThorneResearchGroup/repositories?q=Morse&type=all&language=&sort=) - Generate morse code audio recordings

[OpticalCharacterRecognition](https://github.com/orgs/ThorneResearchGroup/repositories?q=OpticalCharacterRecognition&type=all&language=&sort=) - Send it an image, and it will return the text found within the image

### Libraries:

[Palila Web Framework](https://github.com/ThorneResearchGroup/WebFramework)

[Cache Access Object](https://github.com/ThorneResearchGroup/CAO)

[Database Access Object](https://github.com/ThorneResearchGroup/DAO)

[Search Access Object](https://github.com/ThorneResearchGroup/SAO)

[JSON](https://github.com/ThorneResearchGroup/Library-JSON)

### Projects:

[Galago](https://github.com/orgs/ThorneResearchGroup/repositories?q=galago&type=all&language=&sort=)













For the praise and glory of His name. All honour and glory are His, now and forever.
cUPPr_AilTM
