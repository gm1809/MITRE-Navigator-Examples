Creating Examples via MITRE ATT&CK Navigator

This document outlines the steps to compare the TTPS of two distinct ATPs using MITRE Navigator interace.

This document outlines the steps to create two examples using the web-based MITRE ATT&CK Navigator platform: one comparing Sandworm vs APT28 and another for NoTpetya.
Prerequisites

    Access the Web-Based Navigator:
    Navigate to the MITRE ATT&CK Navigator web application. No local installation is required.
    MITRE ATT&CK Framework Data:
    Familiarize yourself with the MITRE ATT&CK framework and review the tactics and techniques available.

Steps to Create the Examples:

1. Access the Navigator

Open your web browser and go to the MITRE ATT&CK Navigator.
2. Create a New Layer File

    Click on "New Layer" to open a blank visualization workspace.
    Choose Enterprise ATT&CK Domain.
    This layer will be used to map out your attack scenarios.

3. Identify and Map Techniques
Sandworm vs APT28 Example
Create a Layer for Each Group

Sandworm:

    Search for the Sandworm Team under Threat Groups.
    Click Select to mark their TTPs.
    Go to Technique Controls and set a scoring of 1.

APT28:

    Search for APT28 under Threat Groups.
    Click Select to mark their TTPs.
    Go to Technique Controls and set a scoring of 2.

Merging Layers

    Create a new layer by selecting "Create Layer from Other Layers".
    Choose the Enterprise Domain.
    In the Score Expression field, add "a+b" to merge the Sandworm and APT28 layers.
    The merged layer will automatically assign a score of 3 for overlapping techniques (used by both groups) and use different colors to distinguish the unique TTPs.
