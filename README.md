# Boostcamp AI Tech 7 SuperNova

## Hand Bone Image Segmentation
#### 2024.11.13 10:00 ~ 2024.11.28 19:00

뼈는 우리 몸의 구조와 기능에 중요한 영향을 미치므로, 정확한 뼈 분할은 의료 진단 및 치료 계획 수립에 필수적입니다. 

Bone Segmentation은 인공지능 분야에서 중요한 응용 분야 중 하나로, 특히 딥러닝 기술을 활용한 뼈 Segmentation에 대한 연구가 활발히 진행되고 있습니다. 이는 다양한 목적으로 활용될 수 있습니다.

- **질병 진단**: 뼈의 형태나 위치가 변형되거나 부러진 경우, 해당 부위의 문제를 정확히 파악하여 적절한 치료를 시행할 수 있습니다.
- **수술 계획**: 의사들은 뼈 구조를 분석하여 필요한 수술의 종류와 사용할 재료를 결정할 수 있습니다.
- **의료 장비 제작**: 인공 관절이나 치아 임플란트를 제작할 때, 뼈 구조를 분석하여 적절한 크기와 모양을 결정하는 데 필요한 정보를 제공합니다.
- **의료 교육**: 의사들은 병태 및 부상에 대한 이해를 높이고, 수술 계획을 개발하는 데 필요한 기술을 연습할 수 있습니다.


![image](https://github.com/user-attachments/assets/1f72f09c-21ca-4aec-96fc-db8a5d0a89ce)

저희들이 개발한 우수한 성능의 모델은 질병 진단, 수술 계획, 의료 장비 제작, 의료 교육 등 다양한 분야에서 활용될 것으로 기대됩니다. 🌎

### Input
- Hand bone X-ray 객체가 담긴 이미지가 모델의 입력으로 사용됩니다.
- Segmentation annotation은 JSON 파일로 제공됩니다.

### Output
- 모델은 각 클래스(29개)에 대한 확률 맵을 생성하고, 이를 기반으로 각 픽셀을 해당 클래스에 할당합니다.
- 최종적으로 예측된 결과는 Run-Length Encoding(RLE) 형식으로 변환되어 CSV 파일로 제출됩니다.

## Result


## Contributors

| 팀원 이름 | 이미지 |
|-----------|--------|
| [김동영](https://github.com/kimdyoc13) | ![김동영](https://private-avatars.githubusercontent.com/u/116950743?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MzE1MDA3NjAsIm5iZiI6MTczMTQ5OTU2MCwicGF0aCI6Ii91LzExNjk1MDc0MyJ9.kQDdSTPb8RiHaE_7ow9AVnKX0Ta3UEbwwMsp_SM9HvE&v=4) |
| [김예나](깃허브 주소 2) | ![김예나](이미지 주소 2) |
| [은예찬](깃허브 주소 3) | ![은예찬](이미지 주소 3) |
| [임동훈](깃허브 주소 4) | ![임동훈](이미지 주소 4) |
| [정아영](깃허브 주소 5) | ![정아영](이미지 주소 5) |
| [한승수](깃허브 주소 6) | ![한승수](이미지 주소 6) |

## Product Structure

## Usage

## Requirements





