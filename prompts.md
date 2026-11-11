# 테스트에 쓴 프롬프트 모음

모든 프롬프트 뒤에는 `, best quality, highly detailed` 가 자동으로 붙습니다.

**네거티브 프롬프트 (공통)**
`lowres, bad anatomy, extra limbs, extra fingers, missing fingers, deformed, blurry, worst quality`

## 기본 생성 (셀 5)
| 파일 | 포즈 | 프롬프트 | seed |
|---|---|---|---|
| output_01.png | pose_01 | an astronaut in a white space suit on the moon, photo | 42 |
| output_02.png | pose_02 | a knight in shining armor in a medieval castle, photo | 42 |

## 실험 A — 같은 포즈, 다른 프롬프트 (셀 7)
| 파일 | 포즈 | 프롬프트 | seed |
|---|---|---|---|
| expA_1.png | pose_01 | a chef in a white uniform in a kitchen, photo | 42 |
| expA_2.png | pose_01 | a superhero in a red cape on a city rooftop, comic style | 42 |
| expA_3.png | pose_01 | a robot made of shiny metal in a factory, 3d render | 42 |

## 실험 B — 같은 프롬프트, 다른 포즈 (셀 8, 8-2)
| 파일 | 포즈 | 프롬프트 | seed | pose_strength |
|---|---|---|---|---|
| expB_pose1.png | pose_01 | a factory worker in a white safety helmet and work uniform, photo | 7 | 1.0 |
| expB_pose2.png | pose_02 | a factory worker in a white safety helmet and work uniform, photo | 7 | 1.0 |
| expB_strength_0.5.png | pose_01 | (같음) | 7 | 0.5 |
| expB_strength_1.0.png | pose_01 | (같음) | 7 | 1.0 |
| expB_strength_1.5.png | pose_01 | (같음) | 7 | 1.5 |
| expB_pose2_strength_0.5.png | pose_02 | (같음) | 7 | 0.5 |
| expB_pose2_strength_1.0.png | pose_02 | (같음) | 7 | 1.0 |
| expB_pose2_strength_1.5.png | pose_02 | (같음) | 7 | 1.5 |

## 참조 사진 (Gemini로 생성)
| 파일 | 자세 |
|---|---|
| pose_01.png | 나무 의자에 옆으로 앉은 여성 |
| pose_02.png | 오른손을 높이 들어 인사하는 남성 |
