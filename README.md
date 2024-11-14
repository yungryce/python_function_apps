# Azure Function Apps Repository

This repository contains multiple Azure Function Apps, each serving distinct purposes across various domains, from authentication to image processing, reCAPTCHA verification, and virtual machine management.

## Function Apps Overview

### 1. **Auth_FA**
   - **Description:** Manages user authentication, including registration, login, and token-based access control.
   - **Key Endpoints:** 
     - `/register`
     - `/login`
     - `/logout`
     - `/get_user/{username}`

### 2. **Email_FA**
   - **Description:** Handles email dispatch for notifications, user verification, and alerts.
   - **Features:** SMTP integration, customizable email templates, and logging.

### 3. **recaptcha_FA**
   - **Description:** Integrates Google reCAPTCHA v3 for token verification and risk assessment to secure client actions.
   - **Main Method:** `verify_recaptcha` – Verifies client-generated reCAPTCHA tokens.

### 4. **ImageProcessor_FA**
   - **Description:** Compresses, stores, and retrieves images using Azure Blob Storage.
   - **Key Features:** Image compression to under 20 KB, storage, and retrieval from Azure Blob Storage.

### 5. **startstopVM_FA**
   - **Description:** Manages the automated start and stop of Azure VMs based on a scheduled timer trigger.
   - **VM Management:** Supports scheduled VM power-on and power-off for cost optimization.

## Setup and Installation

Each Function App is included in this repository as a submodule. To clone this repository with submodules, use:

```bash
git clone --recurse-submodules <repository-url>
```


Memory updated
Here’s a straightforward README.md for the repository holding your Azure Function Apps as submodules:

markdown
Copy code
# Azure Function Apps Repository

This repository contains multiple Azure Function Apps, each serving distinct purposes across various domains, from authentication to image processing, reCAPTCHA verification, and virtual machine management.

## Function Apps Overview

### 1. **Auth_FA**
   - **Description:** Manages user authentication, including registration, login, and token-based access control.
   - **Key Endpoints:** 
     - `/register`
     - `/login`
     - `/logout`
     - `/get_user/{username}`

### 2. **Email_FA**
   - **Description:** Handles email dispatch for notifications, user verification, and alerts.
   - **Features:** SMTP integration, customizable email templates, and logging.

### 3. **recaptcha_FA**
   - **Description:** Integrates Google reCAPTCHA v3 for token verification and risk assessment to secure client actions.
   - **Main Method:** `verify_recaptcha` – Verifies client-generated reCAPTCHA tokens.

### 4. **ImageProcessor_FA**
   - **Description:** Compresses, stores, and retrieves images using Azure Blob Storage.
   - **Key Features:** Image compression to under 20 KB, storage, and retrieval from Azure Blob Storage.

### 5. **startstopVM_FA**
   - **Description:** Manages the automated start and stop of Azure VMs based on a scheduled timer trigger.
   - **VM Management:** Supports scheduled VM power-on and power-off for cost optimization.

## Setup and Installation

Each Function App is included in this repository as a submodule. To clone this repository with submodules, use:

```bash
git clone --recurse-submodules <repository-url>
```

## Usage
Each Function App is structured as an independent project with its own set of dependencies and environment configurations. Refer to each app's specific README.md for setup and usage instructions.

## Contributing
Contributions to individual Function Apps or new Function Apps are welcome. Please submit pull requests to the appropriate submodule repository.

## License
This project is licensed under the MIT License.

