# Conway's Game Of Life AI 
(English | 한국어)
## Project Overview | 프로젝트 개요
*English*

The goal of this project is to implement Conway's Game of Life so that the user-uploaded or selected image becomes the final target pattern. By blending Conway's rules with probabilistic adjustments, the simulation gradually transforms the grid to match the user-defined target image.

- Starting from a random initial grid, the simulation uses Conway's rules and probabilistic adjustments to gradually align with the target image.
- Detailed implementation and methodology can be found in the Final Report.

*한국어*

이 프로젝트의 목표는 Conway's Game of Life를 사용자가 업로드하거나 선택한 이미지가 최종 목표 이미지가 되도록 구현하는 것입니다.
Conway 게임의 규칙과 확률적 조정을 결합해 시뮬레이션이 점진적으로 그리드를 사용자가 정한 목표 이미지와 일치하도록 변환하였습니다.

- 초기 상태는 랜덤하게 생성된 그리드에서 시작하며, Conway 게임의 규칙과 확률적 조정을 통해 시간이 지남에 따라 목표 이미지와 점진적으로 일치하게 됩니다.
- 구현 및 방법에 대한 더 자세한 내용은 Final Report에서 확인하실 수 있습니다.

## How to Run | 실행 방법
*English*

1. Adjust sample file paths in conway.py
   Open conway.py and locate lines 124-126. Modify the file paths for the sample images to match your system's directory structure.
   
```python
preselected_images = { 
    "Sample Image 1": r"path_to_your_system\sample_image1.jpg",
    "Sample Image 2": r"path_to_your_system\sample_image2.jpg",
    "Sample Image 3": r"path_to_your_system\sample_image3.jpg",
}
```
2. Run the program
   1. Execute the conway.py file:
      ```python
      python conway.py
    2. A GUI window like the following will apear:
       ![스크린샷 2025-01-10 235321](https://github.com/user-attachments/assets/fb6f5e2a-c3f8-4a05-87ce-d0088f1842ef)
       
       <image 1 | 그림 1>
     - **Select or Uploade an Image**
        - Choose one of the preloaded images (Sample Image 1, Sample Image 2, Sample Image 3) by clicking on it.
        - Alternatively, click "Upload Your Own Image" to upload a custom image from your computer.
     - **Start the Animation**
        - Once you’ve selected or uploaded an image, click "Start Animation" to begin the simulation.
        - The grid will evolve according to Conway's Game of Life rules, gradually aligning with the target image.
       
*한국어*

1. conway.py에서 샘플 파일 경로 조정
   conway.py 파일을 열고 124-126번째 줄을 찾아서 샘플 이미지 경로를 컴퓨터의 디렉토리 구조에 맞게 수정해주세요.
2. 프로그램 실행
   1. conway.py 파일을 실행하세요:
      ```python
      python conway.py
    2. 실행 후 그림1과 같은 GUI 창이 나타납니다
   - **이미지 선택 또는 업로드**
     - 샘플 이미지(Sample Image 1, Sample Image 2, Sample Image 3) 중 하나를 클릭해 선택하세요.
     - 또는, "Upload Your Own Image" 버튼을 클릭하여 컴퓨터에서 사용자 정의 이미지를 업로드하세요.
   - **애니메이션 시작**
     - 이미지를 선택하거나 업로드한 후 "Start Animation" 버튼을 클릭하여 시뮬레이션을 시작하세요.
      - Conway의 Game of Life 규칙에 따라 그리드가 진화하며 점진적으로 목표 이미지와 일치하게 됩니다.


