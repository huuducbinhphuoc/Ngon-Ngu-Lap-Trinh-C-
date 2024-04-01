bài 1 
#include <stdio.h>

int main() {
    int start = 7; // Bắt đầu từ 7
    int end = 99; // Kết thúc tại 99

    printf("Cac so nguyen co 2 chu so va la boi cua 7:\n");
    for (int i = start; i <= end; i += 7) {
        printf("%d ", i);
    }

    return 0;
}
