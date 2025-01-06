# LabAssist-Prod
Production repository for LabAssist

To use:
1. Install & setup docker desktop
2. Run `docker compose pull` from this directory
3. Run `docker compose up` to start the application
4. Open `http://localhost:3000` to view

Note:
 - This application requires a Compute Capability of >3.5 (Minimum GTX 1050 and above), GPU must be Nvidia
 - Docker engine must be initialized to run the application (open docker desktop)
 - If you get an error like: `open //./pipe/dockerDesktopLinuxEngine: The system cannot find the file specified.`
    1. Open a new terminal
    2. Run `cd "C:\Program Files\Docker\Docker"`
    3. Run `./DockerCli.exe -SwitchLinuxEngine`