# Mirror Change Script

This script allows you to change the mirror server of your Ubuntu or CentOS system. The list of mirrors in this script is based on Korean mirrors, but you can manually enter any mirror URL or modify the script to include mirrors from other countries. You can refer to [this link](https://launchpad.net/ubuntu/+archivemirrors) for a list of mirrors by country.

**Note:** This script was originally developed for switching to Korean mirror servers, but you can modify the script or manually input the mirror URL to suit your country.


## Usage

1. Run the script as root or with sudo.
2. Select a mirror from the list or enter a mirror URL manually.
3. The script will change the mirror server in your system's sources.list (for Ubuntu) or .repo files (for CentOS).

**Note:** The script will make a backup of your current sources.list or .repo files before making any changes. If you want to revert back to the original mirror server, you can select the "Rollback" option from the mirror list.

## Requirements

* Ubuntu or CentOS system
* Root privileges


## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

---

# 미러 변경 스크립트

이 스크립트를 사용하면 Ubuntu 또는 CentOS 시스템의 미러 서버를 변경할 수 있습니다. 이 스크립트에 포함된 미러 목록은 한국 미러를 기반으로 하지만, 사용자는 어떤 미러 URL도 수동으로 입력하거나 스크립트를 수정하여 다른 국가의 미러를 포함시킬 수 있습니다. 국가별 미러 목록은 [이 링크](https://launchpad.net/ubuntu/+archivemirrors)를 참조하십시오.

**참고:** 이 스크립트는 원래 한국 미러 서버로 전환하기 위해 개발되었지만, 사용자의 국가에 맞게 스크립트를 수정하거나 미러 URL을 수동으로 입력할 수 있습니다.

## 사용법

1. root 또는 sudo로 스크립트를 실행합니다.
2. 목록에서 미러를 선택하거나 미러 URL을 수동으로 입력합니다.
3. 스크립트는 시스템의 sources.list(우분투의 경우) 또는 .repo 파일(센트OS의 경우)에서 미러 서버를 변경합니다.

**참고:** 스크립트는 변경을 수행하기 전에 현재의 sources.list 또는 .repo 파일의 백업을 만듭니다. 원래의 미러 서버로 돌아가려면 미러 목록에서 "롤백" 옵션을 선택할 수 있습니다.

## 요구 사항

* Ubuntu 또는 CentOS 시스템
* 루트 권한

## 라이선스

이 프로젝트는 MIT 라이선스에 따라 라이선스가 부여됩니다. 자세한 내용은 [라이선스](LICENSE) 파일을 참조하십시오.
