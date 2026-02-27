# QML-VTK-Python (PySide6 + VTK 9.x)

This project is a modernized Qt6 / PySide6 and VTK 9.x version of the original Qml-VTK-Python implementation:
https://github.com/dao-duc-tung/Qml-VTK-Python

The original project was based on **PySide2 + VTK 8.x (Qt5)**.

This fork updates the project to work with:

- Python 3.12
- PySide6 (Qt6)
- VTK 9.6.0

The internal architecture and rendering approach remain the same as the original project.  
Only compatibility and version-related updates were applied.

---

## Changes in This Fork

- Migrated **PySide2 → PySide6**
- Migrated **Qt5 → Qt6**
- Migrated **VTK 8.x → VTK 9.6.0**
- Updated imports and API differences for Qt6 compatibility
- Tested on Python 3.12 (Windows)

---

## Tested Environment

```
Python 3.12
PySide6 6.10.2
VTK 9.6.0
Windows 11
```

Install:

```bash
conda create --name QmlVtk python=3.12
conda activate QmlVtk

pip install PySide6==6.10.2 vtk==9.6.0
```

---

## Original Project

For full architectural details and documentation,  
please refer to the original repository:

https://github.com/dao-duc-tung/Qml-VTK-Python


----------------------------------------------------------------------



# QML-VTK-Python (PySide6 + VTK 9.x)

이 프로젝트는 기존 Qml-VTK-Python 구현을 Qt6 / PySide6 및 VTK 9.x 환경에 맞게 현대화한 버전입니다:
https://github.com/dao-duc-tung/Qml-VTK-Python

기존 프로젝트는 **PySide2 + VTK 8.x (Qt5)**를 기반으로 구축되었습니다.

본 저장소는 다음과 같은 최신 환경에서 동작하도록 업데이트되었습니다:

- Python 3.12
- PySide6 (Qt6)
- VTK 9.6.0

내부 아키텍처 및 렌더링 방식은 원본 프로젝트와 동일하게 유지되었으며, **버전 호환성 및 API 변경 사항**만 수정하여 반영하였습니다.

---

## 변경 사항 (Changes)

- **PySide2 → PySide6** 마이그레이션
- **Qt5 → Qt6** 마이그레이션
- **VTK 8.x → VTK 9.6.0** 마이그레이션
- Qt6 호환성을 위한 임포트(Import) 및 API 차이점 수정
- Python 3.12 환경 테스트 완료 (Windows)

---

## 테스트 환경 (Tested Environment)

```text
Python 3.12
PySide6 6.10.2
VTK 9.6.0
Windows 11
```

## 설치 방법
```bash
conda create --name QmlVtk python=3.12
conda activate QmlVtk

pip install PySide6==6.10.2 vtk==9.6.0
```


## 원본 프로젝트 (Original Project)
상세한 아키텍처 설계 및 관련 문서는 원본 저장소를 참조하시기 바랍니다:

https://github.com/dao-duc-tung/Qml-VTK-Python
