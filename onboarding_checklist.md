# Onboarding Checklist

## 1. Network Infrastructure
### Core Network Overview
- [ ] Network topology documentation
- [ ] Physical network diagram
- [ ] Logical network diagram
- [ ] Physical networking asset inventory (switches, APs, P2PoE, etc)

### IP Addressing
- [ ] IP address scheme
- [ ] IPv4/IPv6 subnets
- [ ] VLAN assignments
- [ ] DHCP Server Assignments
- [ ] DHCP scopes and reservations
- [ ] DNS records and zones
- [ ] DNS servers

### Network Security
- [ ] Firewall configuration
- [ ] Special Rules documentation (port forwarding, etc)
- [ ] DMZ configuration

### Remote Access
- [ ] Client VPN solution
- [ ] Site-to-site VPN?
- [ ] MFA integration?
- [ ] Remote access policies - BYOD, split/full tunnel, etc

## 2. Server Infrastructure
### Physical Servers
- [ ] Physical Server inventory
- [ ] CPU/RAM/Storage configurations
- [ ] RAID configurations
- [ ] Power redundancy

### Virtual Infrastructure
- [ ] Virtual Server inventory
- [ ] Hypervisor platform details
- [ ] Hypervisor configuration details
- [ ] Resource pools
- [ ] VM templates
- [ ] Host clusters

### Storage Systems
- [ ] SAN/NAS configuration
- [ ] File share configuration
- [ ] Storage pools
- [ ] Storage network configuration
- [ ] Backup platform/schedule

## 3. Server Configuration
### Active Directory
- [ ] Domain structure
- [ ] Forest/domain layout
- [ ] Trust relationships
- [ ] OU structure
- [ ] GPO inventory
- [ ] FSMO roles

### Email System
- [ ] Exchange/Office 365 configuration
- [ ] Mail flow rules
- [ ] Connectors/SMTP relays
- [ ] Distribution groups - noteworthy/organization wide (for user setup document purposes)
- [ ] Compliance settings
- [ ] Anti-spam configuration
- [ ] Mail Policies (mobile device, archive, sharing)

## 4. Security Infrastructure
### Access Control  
- [ ] Password policies
- [ ] MFA implementation
- [ ] SSO configuration
- [ ] Just-in-time access

### Physical Security
- [ ] Physical Access Policies (doors, keycards, locks)
- [ ] Surveillance System/NVR
- [ ] Camera Footage Policies (backup/retention)

## 5. Endpoint Management
### Physical Inventory Management
- [ ] Workstation Inventory
- [ ] Hardware Asset Tracking (printers, cameras, IOT)
- [ ] Mobile Device Inventory

### OS/Software Management
- [ ] Local admin policies
- [ ] Standard software stack

### User Profile/Data Management
- [ ] Folder redirection
- [ ] Home drive
- [ ] OneDrive/User backup settings

### Endpoint Security
- [ ] Antivirus/EDR solution
- [ ] Policy configuration
- [ ] Exclusions
- [ ] Update schedule (if custom)
- [ ] Encryption status - bitlocker or other y/n
- [ ] High risk users

## 6. Backup & Disaster Recovery
### Backup Systems
- [ ] Backup infrastructure
- [ ] Backup schedules
- [ ] Data retention policies
- [ ] Recovery testing schedule

### Disaster Recovery
- [ ] DR site configuration
- [ ] Replication settings
- [ ] Failover procedures
- [ ] Recovery order
- [ ] DNS failover
- [ ] Breakglass/backup admin accounts for 365 & LOB apps

## 7. Application Infrastructure
### Business Applications
- [ ] Application inventory
- [ ] Version information
- [ ] Dependencies
- [ ] Service accounts
- [ ] Integration points
- [ ] Licensing Information
- [ ] Application Champions

### Web Infrastructure
- [ ] Web server configuration
- [ ] IIS/Apache/Nginx settings
- [ ] SSL certificates
- [ ] Virtual hosts
- [ ] CDN setup
- [ ] Domain Registrar

## 8. Cloud Infrastructure
### Cloud Services
- [ ] MDM management
- [ ] Cloud platform
- [ ] Resource groups
- [ ] Network setup
- [ ] Security groups
- [ ] Cost management
- [ ] Compliance settings
- [ ] Licensing information

### Hybrid Infrastructure
- [ ] AD Sync

## 9. Business Information
- [ ] Liason Details (who to call, when, and where)
- [ ] Location Information
- [ ] Hours of Operation
- [ ] Org Chart (if applicable)
- [ ] Quirks - eg. "don't call xyz, only email" etc


# Maintainence Checklist

## 1. Technical Account Details
### Technical Documentation Requirements
- [ ] Domain admin credentials
- [ ] Service account inventory
- [ ] Vendor portal access
- [ ] Network device access
- [ ] Backup system access
- [ ] Network diagrams (Visio/draw.io)
- [ ] Server build documentation
- [ ] DR runbook
- [ ] Standard operating procedures
- [ ] Physical security policies
- [ ] Incident response playbooks

### Technical Debt Assessment
- [ ] Legacy systems inventory
- [ ] Unsupported software
- [ ] End-of-life hardware
- [ ] Security vulnerabilities
- [ ] Capacity constraints
- [ ] Documentation gaps

### Integration Points
- [ ] Authentication systems
- [ ] Backup systems
- [ ] Cloud services
- [ ] Third-party services
- [ ] External vendors (access to internal systems y/n)

## Notes:
- Document all custom scripts and automation
- Keep security exceptions documented

## To Add:
- more VOIP information
- warranty expirations, cable management
    printers (scan to email, fax (efax or old fax), gpo need, 3rd party print management), 
- Default GPOs: GPO for computers do not sleep