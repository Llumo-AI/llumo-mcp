# LLumo Evaluation System
## Claude Desktop Installation & Usage Guide

_Professional documentation provided by © LLumo.ai_

---

## 👋 Welcome
Welcome to the **LLumo Evaluation System** for Claude Desktop. This guide will help you set up and configure your environment.

## 📋 Prerequisites

> [!IMPORTANT]
> Please ensure the following are installed before proceeding:
> *   **Claude Desktop:** Installed on your computer (Windows or Mac).
> *   **Node.js:** **REQUIRED**. [Download the LTS version here](https://nodejs.org).

---

## 🚀 Installation Steps

### 1. Download and Extract
1.  Download the ZIP file.
2.  Extract the archive. You should see two key files.

<img src="https://github.com/user-attachments/assets/0b3a25e8-ef36-4025-8e16-dee4c141733e" alt="Zip" width="320" />

### 2. Install the MCP Server
1.  Run `llumo-mcpp-server claude` by double-clicking it.
2.  Double-click the `.mcpb` file to start installation.
3.  **Note:** If prompted to "Select an app" and Claude Desktop is running:

| Platform | Instructions |
| :--- | :--- |
| **Windows** | 1. Select "Choose an app on your PC"<br>2. Paste `%LocalAppData%\AnthropicClaude\` into address bar<br>3. Select `Claude.exe` |
| **Mac** | 1. Select "Other..."<br>2. Press **Cmd+Shift+G**<br>3. Paste `/Applications/Claude.app`<br>4. Click Open |

<img src="https://github.com/user-attachments/assets/e5cb0817-6d02-4013-9a3c-566d32e11d07" alt="Llumo-mcp-install" width="800" />

> [!WARNING]
> **Permissions Required**
> Installation requires privileges for setup purposes only. No changes will be made to your user data or other applications.

<img src="https://github.com/user-attachments/assets/c0ae0cdc-355a-4e3d-ba68-1813fd80c6fb" alt="warning" width="1000" />

4.  Click **Install** in Claude Desktop and wait 1-2 minutes.

<img src="https://github.com/user-attachments/assets/80b3f629-5dba-40a9-b217-972b9d297515" alt="Llumo_Api_key" width="800" />

### 3. Configure API Key & Extensions

#### A. Get your API Key
Sign in to [app.llumo.ai/getting-started](https://app.llumo.ai) and copy your **LLumo API Key**.

<img src="https://github.com/user-attachments/assets/b99f452b-4df7-4432-9011-a95d0623e4c5" alt="Llumoapikey" width="800" />

#### B. Setup Extensions
1.  Enable the extension if disabled.

    ![disabled](https://github.com/user-attachments/assets/d94b8743-bbe5-4f23-bc24-56fe50433fe7)

2.  Go to `Settings` -> `Extensions` -> `Browse extensions`.

    ![Extension](https://github.com/user-attachments/assets/1c43bb63-46ce-43f0-95ec-055e138c97b4)

3.  Search for and install **"Filesystem"**.
    ![search](https://github.com/user-attachments/assets/55c2f320-9f93-4fee-b5b3-0ac9b44ab7d6)

    > The Filesystem extension enables Claude to interact with local files.

    | Tool Name | Description |
    | :--- | :--- |
    | `read_file` | Read a single file's content. |
    | `write_file` | Create or overwrite a file. |
    | `list_directory` | List contents of a folder. |

4.  Configure **Filesystem** permissions for your evaluation documents folder.

    ![configure filesystem](https://github.com/user-attachments/assets/a176f87e-493c-4a66-82ad-e2a4141fa8ba)

5.  Ensure **Filesystem** and **llumo-mcp-server** are both **Installed** and **Enabled**.

    ![Both](https://github.com/user-attachments/assets/5012ef11-5a54-415e-a2bc-b3e18add144a)

---

### 4. Verify Connection

> [!TIP]
> **Verification Check**
> Open a new chat in Claude and ask: **"Llumo is connected?"**

![connected](https://github.com/user-attachments/assets/b9abaf4d-677f-4839-a46a-8e11b8d42a53)

*   **Success:** If the status is good, you are ready!
*   **Manual Config:** If needed, set the key manually by typing:

```text
Set my LLUMO API key to: your_api_key_here
```

<img src="https://github.com/user-attachments/assets/4861d694-b45d-409f-9e40-d28ce30a7f22" width="600"/>

✨ **_acme_test_data_150_rows_with_metrics.xlsx_** — Evaluate all rows in this Excel file for **Hallucination**, **Response Completeness**, and **Input Toxicity** using **llumo.ai**, and create a **simplified UI** to present the findings.

**Report**

<img src="https://github.com/user-attachments/assets/fda34255-9737-43cd-ba8d-eb145e08fc24" width="600"/>

<img src="https://github.com/user-attachments/assets/80ca509b-d838-4eb4-98df-e6c979bce51a" width="600"/>

<img src="https://github.com/user-attachments/assets/11599e6c-0aa0-4863-aa7c-c3437c8aa2c7" width="600"/>

<img src="https://github.com/user-attachments/assets/7362bf41-8c1c-43ec-86db-bd16b20435cb" width="600"/>

<img src="https://github.com/user-attachments/assets/4a043bc8-7948-4b88-960a-a368bfa70b06" width="600"/>

<img src="https://github.com/user-attachments/assets/20c50ba8-c46a-4dad-9e31-40db66aa3a71" width="600"/>









