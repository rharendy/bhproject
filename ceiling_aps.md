Setting up Ubiquiti Access Points (APs) on the ceiling in a two-story house can significantly improve Wi-Fi coverage and signal strength. Here’s a step-by-step guide:

### 1. **Plan AP Placement**
   - **Primary Goal**: Position APs to maximize coverage on each floor without significant overlap or interference.
   - **Typical Placement**:
     - **One AP per Floor**: Place each AP roughly in the center of each floor to ensure even coverage.
     - **High-traffic Areas**: Prioritize spaces like the living room, office, or kitchen, where connectivity is often in demand.
     - **Avoid Walls/Obstructions**: Keep APs away from thick walls, metal objects, or large appliances, which can obstruct the Wi-Fi signal.

### 2. **Use PoE (Power over Ethernet)**
   - **PoE Injector or Switch**: Connect your Ubiquiti APs via Ethernet cables to a PoE-enabled switch or PoE injector, which provides both power and data over a single cable.
   - **Cable Type**: Use Cat6 or Cat6a Ethernet cables for reliable performance and future-proofing.

### 3. **Mount APs on the Ceiling**
   - **Mounting Kit**: Most Ubiquiti APs come with a ceiling mounting kit. Follow the provided instructions to securely mount the AP to the ceiling.
   - **Positioning**: Place the APs in a downward-facing position on the ceiling for optimal signal coverage.
   - **Concealing Cables**: Run Ethernet cables through the ceiling or wall, if possible, to keep the setup neat.

### 4. **Connect APs to the Network**
   - Connect each AP via Ethernet to the PoE switch in your central network equipment location (e.g., in the garage).
   - Ensure that the switch is connected to your main router for internet access.

### 5. **Configure the APs with UniFi Controller**
   - **Install UniFi Controller**: Use the UniFi Network application (install it on a computer or access it from the UniFi Cloud) to manage and configure your Ubiquiti APs.
   - **Adopt APs**: Log in to the UniFi Controller, and adopt each AP by following the setup prompts. 
   - **Basic Settings**:
     - **SSID**: Create or assign an SSID (network name) for each AP.
     - **Channel Settings**: Manually assign different channels for each AP to reduce interference between floors.
     - **Transmit Power**: Adjust power levels to avoid excessive overlap between floors, which can reduce roaming performance.

### 6. **Optimize Wi-Fi Coverage**
   - **Testing**: After installation, test Wi-Fi coverage on both floors to ensure there are no dead zones.
   - **Adjustments**: If you notice overlap or weak signal areas, consider adjusting the transmit power or relocating an AP.

### 7. **Enable Seamless Roaming (Optional)**
   - **Fast Roaming**: Ubiquiti’s Fast Roaming feature allows devices to switch seamlessly between APs as users move through the house. This is particularly useful in a multi-floor setup.

By following these steps, you’ll achieve consistent Wi-Fi coverage across both floors with minimal interference and optimized connectivity.
