# 🎨 LUTverter

**No-Setup, Portable Video Lookup Table Processor**

LUTverter는 FFmpeg 엔진이 내장된 단일 실행 파일로, 별도의 설치나 설정 없이 여러 영상 파일에 복수의 LUT(.cube)를 적용하고 원하는 포맷으로 빠르게 변환해주는 전문가용 GUI 도구입니다.

---

## ✨ 핵심 기능 (Key Features)

*   **⚡ All-in-One Portable:** FFmpeg이 내장되어 있어 실행 파일 하나로 어디서든 즉시 작업이 가능합니다.
*   **🎬 Recipe Book (LUT Chaining):** 여러 개의 LUT 파일을 체인처럼 연결하여 순차적으로 적용할 수 있습니다.
*   **👀 실시간 프리뷰:** 변환 과정 중에 원본(좌)과 LUT 적용 후(우)의 모습을 나란히 비교하며 확인할 수 있습니다.
*   **📦 고성능 인코딩:** H.264(MP4) 뿐만 아니라 영상 편집에 최적화된 Apple ProRes(MOV) 포맷을 지원합니다.
*   **🚀 하드웨어 가속:** 시스템의 GPU(NVIDIA, Intel 등)를 자동으로 감지하여 인코딩 속도를 극대화합니다.
*   **📐 스마트 리사이징:** 원본 대비 25%부터 200%까지 자유로운 출력 해상도 조절이 가능합니다.

---

## 🚀 사용 방법 (How to Use)

본 프로그램은 **무설치 단일 실행 파일(.exe)**로 제공됩니다.

1.  `LUTverter.exe`를 실행합니다.
2.  **Resources**: 변환할 영상 파일들을 드래그하거나 "Add Files" 버튼으로 추가합니다.
3.  **Recipe Book**: 적용할 `.cube` LUT 파일들을 추가합니다. (위에서 아래 순서로 적용됩니다.)
4.  **Settings**: 출력 포맷(H.264 / ProRes)과 품질 프리셋, 출력 크기를 설정합니다.
5.  **Cook!**: "Let's get Cooking!" 버튼을 눌러 변환을 시작합니다.

---

## 🛠 시스템 요구 사항

*   **OS**: Windows 10/11 (64-bit)
*   **Hardware**: 하드웨어 가속(NVENC 등) 지원 그래픽 카드 권장
*   **Portability**: 별도의 코덱이나 엔진 설치가 필요 없습니다.
