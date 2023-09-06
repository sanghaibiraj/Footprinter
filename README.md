# Footprinter

# Domain Information Finder

## Introduction

The Domain Information Finder is a simple Python script that allows you to retrieve information about a domain name. Whether you're a web developer, a security analyst, or just curious about a particular website, this tool provides you with valuable insights into the domain's registration details, DNS records, and more.

## Features

- Retrieve WHOIS information: Get registration details, such as domain owner, registrar, and registration date.
- Display DNS records: Find out the domain's IP address, mail servers, and other DNS-related information.
- Display Geolocation information

## Getting Started

### Prerequisites

Before you can use this script, ensure that you have the following prerequisites installed on your system:

- Python 3.x
- Required Python packages (install using `pip install -r requirements.txt`):
  - `whois`
  - `dnspython`
  - `requests`
  - `sys`
  - `argparse`
  - `socket`

### Usage

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/sanghaibiraj/Footprinter.git
   ```

2. Navigate to the project directory:

    ```shell
    cd Footprinter
    ```

3. Run the script by providing a domain name as an argument:

   ```shell
   python info_gathering.py example.com
   ```

   Replace `example.com` with the domain name you want to look up.

4. The script will provide you with information about the specified domain, including WHOIS details, DNS records, and geolocation information.


## Contributing

Contributions to this project are welcome! If you have ideas for improvements or new features, please submit an issue or a pull request.


## Acknowledgments

- Special thanks to the creators of the `whois` and `dnspython` libraries for making domain information retrieval easy.
- Inspired by the need for a simple tool to quickly gather domain information.


Happy domain hunting!

