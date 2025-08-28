# VPS Server Configuration Backup

## Server Details
- **Server Name**: vps_fukuku_5906
- **OS**: Ubuntu 25.04
- **UUID**: 778dbda7-e6a7-4062-a8d7-39b3581fb25
- **Host**: host02-2
- **Plan**: VPS 2GB
- **Status**: Running (通常)

## Hardware Specifications
- **vCPU**: 3 cores
- **Memory**: 2GB
- **NVMe SSD**: 50GB

## Network Configuration
- **Standard Host Name**: x162-43-33-16.static.xvps.ne.jp
- **Reverse Host Name**: x162-43-33-16.static.xvps.ne.jp
- **IP Address**: 162.43.33.16

## Security Settings
- **Two-Factor Authentication**: Not configured (未設定)

## Backup Information
- **Backup Date**: 2025-08-28
- **Backup Type**: Server configuration documentation
- **Source**: VPS management panel screenshot

## Recovery Notes
To restore this server configuration:
1. Create new VPS with same specifications (VPS 2GB plan)
2. Install Ubuntu 25.04
3. Configure network settings with the documented IP
4. Restore application files and databases (if backed up separately)
5. Configure DNS settings for the documented hostnames

## Important Files to Backup Separately
- Application configuration files
- Database dumps
- SSL certificates
- Environment variables
- User data and uploads
- Log files
