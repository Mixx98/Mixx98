## Hello World!!


#include <stdio.h>

typedef struct Project {<br/>
    char type[9]; //Team or Personal<br/>
    char url[70]; //Github link<br/>
}P;

int main()<br/>
{<br/>
    char language[49] = "C/C++, Python, JAVA, R, Linux, HTML, CSS, JavaScript";<br/>
    char profileSite[40] = "https://mixx98.github.io/Time_to_Color/";
  
    P GPS와 라이다센서를 이용한 자율주행 RC카 = {"Team", "https://github.com/Mixx98/A-self-driving-car-Project"};
  
    P 초음파 센서를 이용한 전동킥보드 후방센서 = {"Team", "https://github.com/Mixx98/Rear-Sensor-ver.Electric-Kickboard-"};
  
    P 얼굴 면적을 계산해 적정량 만큼 선크림을 짜주는 기계 = {"Team", "https://github.com/Mixx98/Sunblock"};
  
    P 압력센서를 이용한 포인트 차감 게임기 = {"Team", "https://github.com/Mixx98/Punch-Game"};
  
    P 개인 프로필 사이트 = {"Personal", "https://github.com/Mixx98/Time_to_Color"};
  
    P 주류 판매 사이트 = {"Team", "https://github.com/Mixx98/BottleShop"};
  
  
    return 0;<br/>
}

