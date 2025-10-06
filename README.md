# linuxrepo

# Comprehensive Mirror List for RHEL 8 Compatible Distributions
# Updated October 2025 - Including CentOS 8, AlmaLinux 8, Rocky Linux 8, Oracle Linux 8, EPEL 8, and CentOS Stream 8

## TABLE OF CONTENTS
1. CentOS 8 (EOL - Vault Access Only)
2. AlmaLinux 8 (Active)
3. Rocky Linux 8 (Active)
4. Oracle Linux 8 (Active)
5. CentOS Stream 8 (EOL - Archived)
6. EPEL 8 (Active)
7. Red Hat UBI 8 (Active)
8. Geographic Distribution Summary

========================================
1. CENTOS 8 (END OF LIFE - VAULT ACCESS)
========================================

## PRIMARY VAULT REPOSITORY
vault.centos.org - Official CentOS archived repository

## ALTERNATIVE SOURCES
dl.rockylinux.org/vault/centos/ - Rocky Linux hosted CentOS vault
mirrors.edge.kernel.org/centos/ - Kernel.org CDN (HTTPS)

## QUICK FIX REPOSITORY CONFIGURATION
sed -i 's/^mirrorlist/#mirrorlist/g' /etc/yum.repos.d/CentOS-*
sed -i 's|#baseurl=http://mirror.centos.org|baseurl=http://vault.centos.org|g' /etc/yum.repos.d/CentOS-*

========================================
2. ALMALINUX 8 GLOBAL MIRRORS (400+ ACTIVE)
========================================

## PRIMARY REPOSITORIES
repo.almalinux.org - Primary repository
mirrors.almalinux.org - Automatic geolocation-based mirror selection

## NORTH AMERICA
# United States
atl.mirrors.knownhost.com/almalinux/ - Atlanta, GA
mirror.grid.uchicago.edu/pub/almalinux/ - Chicago, IL (University of Chicago)
mirror.liquidweb.com/almalinux/ - Michigan
mirrors.iu13.net/almalinux/ - Pennsylvania (Lancaster-Lebanon IU13)
nnenix.mm.fcix.net/almalinux/ - California (Fremont Cabal)
tx-mirror.tier.net/almalinux/ - Texas (Tier.Net)
mirror.cloudpropeller.com/almalinux/ - Cloud Propeller
stix.mm.fcix.net/almalinux/ - Dominican Republic

# Canada  
mirror.its.dal.ca/almalinux/ - Halifax, NS (Dalhousie University)
ca.mirrors.almalinux.org - Canada regional

## EUROPE
# Netherlands
mirror.nl.leaseweb.net/almalinux/ - Leaseweb
almalinux.mirror.liteserver.nl/ - LiteServer
mirror.serverion.com/almalinux/ - Serverion
eu.edge.kernel.org/almalinux/ - Kernel.org Europe

# Germany
mirror.netzwerge.de/almalinux/ - Hamburg (Netzwerge GmbH)
mirror.rackspeed.de/almalinux/ - rackSPEED GmbH

# United Kingdom
almalinux.linuxpatch.com/ - LinuxPatch.com

# Spain
mirror.raiolanetworks.com/almalinux/ - Madrid (Raiola Networks)
ftp.cixug.es/almalinux/ - Universidade da Coruña

# Finland
almalinux.web.trex.fi/ - TREX Regional Exchanges Oy

# Sweden
mirror.bahnhof.net/almalinux/ - Bahnhof

# Italy
it1.mirror.vhosting-it.com/almalinux/ - VHosting Solution

# Slovenia
mirror.almalinux.si/ - Slovenia mirror

# Bulgaria
mirror.host.ag/almalinux/ - Host.ag

## ASIA-PACIFIC
# China
mirrors.tencent.com/almalinux/ - Tencent
mirror.ossplanet.net/almalinux/ - Taiwan (OSSPlanet)

# Japan
mirrors.xtom.jp/almalinux/ - xTom Japan

# South Korea
mirror.krfoss.org/almalinux/ - ROKFOSS PROJECT
mirror.jeonnam.school/almalinux/ - Jeonnam High School

# Indonesia
mirror.unilak.ac.id/almalinux/ - Lancang Kuning University
dinosaurus.fleksibel.com/almalinux/ - fleksibel.com
mirror.citrahost.com/almalinux/ - Citrahost
mirror.qdei.co/almalinux/ - QDEI Cloud

# Singapore
mirror.freedif.org/almalinux/ - Freedif

# Iran
almalinux.pars.host/ - Pars.Host
ir.almalinux.sindad.cloud/ - Sindad LLC

# Malaysia
mirror.controlvm.com/almalinux/ - ControlVM Sdn Bhd

# Vietnam
mirrors.gofiber.vn/almalinux/ - Gofiber

# Australia
alma.mirror.serversaustralia.com.au/ - Servers Australia
mirrors.nz.zappie.host/almalinux/ - New Zealand (Zappie Host)

## AWS REGIONAL ENDPOINTS
per.aws.repo.almalinux.org - Australia
mnl.aws.repo.almalinux.org - Philippines

========================================
3. ROCKY LINUX 8 GLOBAL MIRRORS (45+ ACTIVE)
========================================

## PRIMARY REPOSITORIES
dl.rockylinux.org - Global CDN (Fastly)
mirrors.rockylinux.org - Mirror selection service

## NORTH AMERICA
# United States
mirror.web-ster.com/rocky/ - DirectLink (10Gbps)
mirror.0xem.ma/rocky/ - Montreal-connected
mirror.reenigne.net/rocky/ - Point-in-time snapshots

# Canada
mirror.cpsc.ucalgary.ca/rocky/ - University of Calgary
mirror.dst.ca/rocky/ - Digital Shape Technologies
mirror.0xem.ma/rocky/ - Montreal, QC (0xEmma)

## EUROPE
# Germany
ftp.fau.de/rocky/ - Friedrich-Alexander-Universität Erlangen-Nürnberg
ftp.halifax.rwth-aachen.de/rocky/ - RWTH Aachen (20Gbps)
mirror.netzwerge.de/rocky/ - Hamburg (Netzwerge GmbH)
mirror.plusline.net/rocky/ - Frankfurt (Plus.line AG)

# Netherlands
mirror.init7.net/rocky/ - Init7 Switzerland AG (20.4Gbps)

# Switzerland
mirror.puzzle.ch/rocky/ - Puzzle ITC

# Czech Republic
ftp.linux.cz/rocky/ - Masaryk University, Brno
ftp.sh.cvut.cz/rocky/ - Prague (Silicon Hill)
mirror.karneval.cz/rocky/ - Prague (Vodafone CZ)
mirror.slu.cz/rocky/ - Opava (Silesian University)

# Denmark
mirror.netsite.dk/rocky/ - Netsite
mirrors.dotsrc.org/rocky/ - DotSrc Aalborg (20Gbps)

# Spain
mirror.raiolanetworks.com/rocky/ - Madrid (Raiola Networks)
mirror.uv.es/rocky/ - Valencia (Universidad de Valencia)

# Finland
mirror.eu.ossplanet.net/rocky/ - OSSPlanet EU

# Austria
rockylinux.anexia.at/rocky/ - Vienna (Anexia)

# Armenia
mirrors.teamcloud.am/rocky/ - Yerevan

# Bulgaria
mirrors.neterra.net/rocky/ - Neterra
mirror.telepoint.bg/rocky/ - telepoint dc

# Azerbaijan
mirror.ourhost.az/rocky/ - OUR Host

## ASIA-PACIFIC
# China
mirror.nju.edu.cn/rocky/ - Nanjing University (10Gbps)
mirror.nyist.edu.cn/rocky/ - Nanyang Institute of Technology

# Chile
mirror.hnd.cl/rocky/ - Hostednode SpA

# Ecuador
mirror.linux.ec/rocky/ - EcuaLinux.com

# Australia
ftp.swin.edu.au/rocky/ - Swinburne University
mirror.aarnet.edu.au/rocky/ - AARNet Melbourne (50Gbps)
rockylinux.mirror.digitalpacific.com.au/rocky/ - Sydney (Digital Pacific)

## GOOGLE CLOUD PLATFORM MIRRORS (CIQ Hosted)
rocky-linux-us-east1.production.gcp.mirrors.ctrliq.cloud/ - US East
rocky-linux-us-west1.production.gcp.mirrors.ctrliq.cloud/ - US West
rocky-linux-europe-west1.production.gcp.mirrors.ctrliq.cloud/ - Belgium
rocky-linux-europe-west3.production.gcp.mirrors.ctrliq.cloud/ - Germany
rocky-linux-europe-west6.production.gcp.mirrors.ctrliq.cloud/ - Switzerland
rocky-linux-australia-southeast1.production.gcp.mirrors.ctrliq.cloud/ - Australia
rocky-linux-southamerica-east1.production.gcp.mirrors.ctrliq.cloud/ - Brazil

========================================
4. ORACLE LINUX 8 REPOSITORIES
========================================

## PRIMARY REPOSITORIES
yum.oracle.com - Official Oracle Linux repository
public-yum.oracle.com - Public access repository

## ORACLE CLOUD INFRASTRUCTURE
objectstorage.us-ashburn-1.oraclecloud.com/yum/ - US Ashburn
objectstorage.eu-frankfurt-1.oraclecloud.com/yum/ - EU Frankfurt  
objectstorage.ap-tokyo-1.oraclecloud.com/yum/ - Asia Pacific Tokyo

## REGIONAL MIRRORS
# North America
mirror.trouble-free.net/oracle-linux/ - Trouble-Free.net
mirror.facebook.com/oracle-linux/ - Facebook CDN

# Europe
oracle-linux.mirrors.uk2.net/ - UK2 Group
mirror.de.oracle-linux.com/ - Germany

# Asia-Pacific
oracle-linux.mirrors.asia/ - Asia regional
mirror.oracle-linux.jp/ - Japan

## REPOSITORY CONFIGURATION EXAMPLE
[ol8_baseos_latest]
name=Oracle Linux $releasever BaseOS Latest ($basearch)
baseurl=https://yum.oracle.com/repo/OracleLinux/OL8/baseos/latest/$basearch/
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-oracle
gpgcheck=1
enabled=1

========================================
5. CENTOS STREAM 8 (EOL - ARCHIVED ACCESS)
========================================

## ARCHIVED REPOSITORIES
vault.centos.org/8-stream/ - Official archived Stream 8
rsync.stream.centos.org - Historical rsync access (limited)

## WORKING MIRRORS (LIMITED)
# European Mirrors (Stream content may be limited)
merlin.fit.vutbr.cz/mirrors/centos/8-stream/ - Czech Republic
mirror-prg.webglobe.com/centos/8-stream/ - Czech Republic
ftp.fi.muni.cz/pub/linux/centos/8-stream/ - Czech Republic
ftp.cvut.cz/centos/8-stream/ - Czech Republic

# Repository Fix for Stream 8 (Vault Migration)
sed -i 's/mirrorlist.centos.org/vault.centos.org/g' /etc/yum.repos.d/CentOS-Stream-*.repo
sed -i 's/^mirrorlist/#mirrorlist/g' /etc/yum.repos.d/CentOS-Stream-*.repo

## Note: CentOS Stream 8 reached EOL on May 31, 2024

========================================
6. EPEL 8 MIRRORS (264+ ACTIVE WORLDWIDE)
========================================

## PRIMARY REPOSITORY
download.fedoraproject.org/pub/epel/8/ - Primary Fedora source

## AUTOMATIC MIRROR SELECTION
mirrorlist.fedoraproject.org/?repo=epel-8&arch=x86_64 - Automatic selection

## NORTH AMERICA
# United States
mirrors.kernel.org/fedora-epel/8/ - Kernel.org (20Gbps)
fedora.melbourneitmirror.net/epel/8/ - Melbourne IT
fedora.mirror.serversaustralia.com.au/epel/8/ - Servers Australia
syd.mirror.rackspace.com/epel/8/ - Rackspace Sydney
gsl-syd.mm.fcix.net/epel/8/ - Fremont Cabal Sydney (100Gbps)

# Canada  
mirror.aarnet.edu.au/pub/epel/8/ - AARNet Melbourne (10Gbps)

## EUROPE
# Austria
centos.anexia.at/epel/8/ - ANEXIA (10Gbps)
mirror.alwyzon.net/epel/8/ - Vienna (Alwyzon)
mirror.nextlayer.at/epel/8/ - next layer GmbH
mirror.digitalnova.at/epel/8/ - Graz (digitalnova.at)

# Netherlands
fedora.cu.be/epel/8/ - Cu.be Solutions (20Gbps, IPv6)

# Bulgaria
epel.uni-sofia.bg/8/ - Sofia University
fedora.ipacct.com/epel/8/ - IPACCT (10Gbps)
mirror.host.ag/epel/8/ - host.ag (2Gbps)
mirrors.neterra.net/epel/8/ - Neterra (2Gbps, IPv6)
mirrors.netix.net/epel/8/ - NetiX (10Gbps)

# Germany
ftp.fau.de/epel/8/ - Friedrich-Alexander-Universität
mirrors.nav.ro/epel/8/ - Romania NAV

# Czech Republic  
ftp.linux.cz/pub/linux/fedora/epel/8/ - Masaryk University

## ASIA-PACIFIC
# Azerbaijan
mirror.yer.az/epel/8/ - YER Hosting Baku (10Gbps)

# China
mirrors.tuna.tsinghua.edu.cn/epel/8/ - Tsinghua University
mirrors.ustc.edu.cn/epel/8/ - University of Science and Technology
mirror.lzu.edu.cn/epel/8/ - Lanzhou University

# Japan
ftp.jaist.ac.jp/pub/Linux/Fedora/epel/8/ - JAIST
ftp.riken.jp/Linux/fedora/epel/8/ - RIKEN

# South Korea
mirror.navercorp.com/epel/8/ - Naver Corporation
ftp.kaist.ac.kr/pub/fedora/epel/8/ - KAIST

# Australia
mirror.realcompute.io/epel/8/ - Real World Group Sydney

========================================
7. RED HAT UBI 8 REPOSITORIES
========================================

## PRIMARY UBI REPOSITORIES (No subscription required)
registry.redhat.io - Container registry
registry.access.redhat.com/ubi8/ - Public access

## UBI YUM REPOSITORIES
# These are pre-configured in UBI containers at /etc/yum.repos.d/ubi.repo

[ubi-8-baseos-rpms]
name=Red Hat Universal Base Image 8 (RPMs) - BaseOS
baseurl=https://cdn-ubi.redhat.com/content/public/ubi/dist/ubi8/8/$basearch/baseos/os
enabled=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-redhat-release
gpgcheck=1

[ubi-8-appstream-rpms]
name=Red Hat Universal Base Image 8 (RPMs) - AppStream
baseurl=https://cdn-ubi.redhat.com/content/public/ubi/dist/ubi8/8/$basearch/appstream/os
enabled=1
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-redhat-release
gpgcheck=1

[ubi-8-codeready-builder-rpms]
name=Red Hat Universal Base Image 8 (RPMs) - CodeReady Builder
baseurl=https://cdn-ubi.redhat.com/content/public/ubi/dist/ubi8/8/$basearch/codeready-builder/os
enabled=0
gpgkey=file:///etc/pki/rpm-gpg/RPM-GPG-KEY-redhat-release
gpgcheck=1

========================================
8. GEOGRAPHIC DISTRIBUTION SUMMARY
========================================

## BEST MIRRORS BY REGION

### NORTH AMERICA
- Primary: mirrors.kernel.org (20Gbps, multi-protocol)
- AlmaLinux: atl.mirrors.knownhost.com (Atlanta)
- Rocky: dl.rockylinux.org (Fastly CDN)
- EPEL: mirrors.kernel.org/fedora-epel

### EUROPE  
- Primary: eu.edge.kernel.org (Netherlands)
- Germany: ftp.fau.de, mirror.netzwerge.de
- Netherlands: mirror.nl.leaseweb.net
- Czech: ftp.linux.cz, ftp.sh.cvut.cz

### ASIA-PACIFIC
- China: mirrors.tencent.com, mirror.nju.edu.cn
- Japan: mirrors.xtom.jp, ftp.jaist.ac.jp  
- Australia: mirror.aarnet.edu.au (50Gbps)
- Singapore: mirror.freedif.org

### HIGH-BANDWIDTH MIRRORS (10Gbps+)
- mirrors.kernel.org (20Gbps) - Global
- mirror.aarnet.edu.au (50Gbps) - Australia
- gsl-syd.mm.fcix.net (100Gbps) - Sydney
- ftp.halifax.rwth-aachen.de (20Gbps) - Germany
- mirrors.dotsrc.org (20Gbps) - Denmark

========================================
STORAGE REQUIREMENTS FOR LOCAL MIRRORING
========================================

## Estimated Mirror Sizes (per architecture)
- Rocky Linux 8 Full: ~50GB (BaseOS + AppStream + PowerTools)
- AlmaLinux 8 Full: ~48GB (BaseOS + AppStream + Extras)
- Oracle Linux 8 Full: ~52GB (BaseOS + AppStream + UEK)
- EPEL 8: ~30GB (Everything + Modular)
- CentOS Stream 8: ~45GB (archived, static size)

## Total for Complete RHEL 8 Ecosystem Mirror: ~225GB

## RSYNC COMMANDS FOR MIRRORING
# AlmaLinux 8
rsync -avH --delete rsync://rsync.repo.almalinux.org/almalinux/8/ /local/mirror/almalinux/8/

# Rocky Linux 8  
rsync -avH --delete rsync://dl.rockylinux.org/rocky/8/ /local/mirror/rocky/8/

# EPEL 8
rsync -avH --delete rsync://download.fedoraproject.org/pub/epel/8/ /local/mirror/epel/8/

========================================
MIGRATION RECOMMENDATIONS
========================================

## PRIORITY MIGRATION ORDER (from CentOS 8)
1. AlmaLinux 8 - Drop-in replacement, 400+ mirrors, enterprise backing
2. Rocky Linux 8 - Community-driven, strong mirror network, CIQ support  
3. Oracle Linux 8 - Enterprise features, cloud integration, Oracle support
4. CentOS Stream 9 - Rolling release, upstream of RHEL 9

## SECURITY NOTES
- CentOS 8: NO security updates since EOL (December 31, 2021)
- CentOS Stream 8: NO security updates since EOL (May 31, 2024)  
- All other distributions: Active security maintenance

## AUTOMATED MIGRATION SCRIPTS AVAILABLE
- alma-migrate: AlmaLinux migration tool
- rocky-migrate: Rocky Linux migration tool  
- oracle-linux-migration: Oracle Linux migration utility

Last Updated: October 6, 2025
Total Active Mirrors: 700+ across all distributions
Coverage: Global with high-bandwidth options in all major regions
