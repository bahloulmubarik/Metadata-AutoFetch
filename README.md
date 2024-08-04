# IPFS File Pinning and Metadata Fetching

This repository includes a Node.js script for pinning files to IPFS using the Pinata API and storing the resulting metadata in a local JSON file.

## How It Works

## Setup

Ensure Node.js is installed on your machine.
Clone the repository and install the necessary dependencies.
Create a .env file with your Pinata API credentials.

## Pinning Files to IPFS

Use the provided function to upload a file to IPFS.
The function will handle the file upload and retrieve its IPFS hash.

## Storing Metadata

The script will save the IPFS metadata, including the hash, into a local JSON file for future reference.

## Error Handling

The script includes error handling to manage issues that may arise during file operations or API requests.

##File Structure

pinFileToIPFS1.js: Handles the file upload to IPFS and processes the response.
ipfsHelper.js: Contains utility functions for managing metadata and file operations.
.env: Stores your Pinata API credentials.

## Contributing
If you would like to contribute to this project, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.
