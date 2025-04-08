<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# Development Guide

Deze gids leidt u door het proces van het opzetten van de ontwikkelomgeving voor het maken van AR-applicaties voor de Meta Quest 3.
Volg deze stappen om uw ontwikkelomgeving gereed te maken en begin met het maken van geweldige projecten.

## Inhoud

- [Benodigheden](#benodigheden)
- [Step 1: Install Unity Hub](#step-1-install-unity-hub)
- [Step 2: Install Unity Editor](#step-2-install-unity-editor)
- [Step 3: Configure Development Environment](#step-3-configure-development-environment)
- [Step 4: Install Required Packages](#step-4-install-required-packages)
- [Step 5: Setting Up Version Control](#step-5-setting-up-version-control)
- [Step 6: Project Structure Best Practices](#step-6-project-structure-best-practices)
- [Troubleshooting](#troubleshooting)
- [Next Steps](#next-steps)

## Benodigheden
- **Visual Studio**
- **Unity**
- **Git en Git Large File Storage**

## Step 1: Install Unity Hub

Unity Hub is a management tool that helps you organize your Unity projects and manage different Unity Editor versions.

1. Go to the [Unity Download page](https://unity.com/download)
2. Click the "Download Unity Hub" button
3. Run the installer and follow the on-screen instructions
4. Launch Unity Hub after installation
5. Sign in with your Unity ID (create one if you don't have it)

> **Note**: Unity offers different license types. For personal use or small teams, the Personal license is free. For commercial projects, you might need a different license.

## Step 2: Install Unity Editor

Once Unity Hub is installed, you need to install the Unity Editor:

1. In Unity Hub, go to the **Installs** tab
2. Click the **Add** button
3. Select the recommended LTS (Long Term Support) version for stability
4. Select the following modules to install:
   - Microsoft Visual Studio Community (or your preferred IDE)
   - Documentation
   - Your target platform(s) (Windows, Mac, Linux, Android, iOS, etc.)
5. Click **Continue** and wait for the installation to complete


## Step 3: Configure Development Environment

Set up your development environment for optimal productivity:

1. **IDE Setup**:
   - Launch Visual Studio or your preferred IDE
   - Install the Unity development extension if available
   - Configure code formatting and linting tools

2. **Unity Preferences**:
   - Open Unity Editor
   - Go to **Edit > Preferences** (Windows/Linux) or **Unity > Preferences** (macOS)
   - Configure External Tools to point to your installed IDE
   - Under **General**, enable **Auto Refresh** for better workflow

3. **Performance Optimization**:
   - In Unity Editor, go to **Edit > Project Settings > Editor**
   - Adjust **Asset Serialization** mode based on your version control needs
   - Configure **Version Control** integration if needed

## Step 4: Install Required Packages

Unity uses a package manager to add functionality to your projects:

1. Create a new project or open an existing one
2. Go to **Window > Package Manager**
3. Install these essential packages for development:
   - **Input System**: For handling player input
   - **Test Framework**: For writing unit tests
   - **Visual Studio Editor**: For better IDE integration
   - **Version Control**: For Git integration
   - Any platform-specific packages you need

```csharp
// Example of using the new Input System
using UnityEngine;
using UnityEngine.InputSystem;

public class PlayerController : MonoBehaviour
{
    private PlayerInput playerInput;
    private Vector2 moveInput;

    private void Awake()
    {
        playerInput = GetComponent<PlayerInput>();
    }

    public void OnMove(InputAction.CallbackContext context)
    {
        moveInput = context.ReadValue<Vector2>();
    }
}
