# Connect Line

A straight mesh connecting two points.

## Install

### OpenUPM

See the [OpenUPM page](https://openupm.com/packages/net.narazaka.unity.connect-line/)

### Installation via unitypackage installer for VCC (Recommended)

Download and extract `net.narazaka.unity.connect-line-installer.zip` from  
https://github.com/Narazaka/ConnectLine/releases/latest,  
then import it into your target project.

### Installation via VCC

1. Go to https://vpm.narazaka.net/ and click the "Add to VCC" button to add the repository to VCC.
2. In VCC, go to Settings → Packages and ensure that "Narazaka VPM Listing" is checked in the list of Installed Repositories.
3. Open "Manage Project" for your avatar project and install "Connect Line".

## Usage

1. Choose either UnityConstraint or VRCConstraint, and place the `LineStart` prefab.
2. Make the `LineStart` and `LineEnd` follow your desired positions using Position Constraint or MA Bone Proxy.

## License

[Zlib License](LICENSE.txt)
