# Code-for-your-Valentine
#include <iostream>

void printHeart() {
    std::cout << R"(
        ******       ******
      **      **   **      **
     **         ** **         **
     **          ***          **
      **                     **
        **                 **
          **             **
            **         **
              **     **
                ** **
                 ***
                  *
    )" << std::endl;
}

int main() {
    std::cout << "A heart for you:" << std::endl;
    printHeart();
    std::cout << "     In your eyes I have found my home In your heart I have found my love In your soul I have found my mate With you I am whole 💖" << std::endl;
    
    std::cout << "    Meeting you was fate becoming your friend was a choice but falling in love with you was beyond my control I love you more than words can say 💞" << std::endl;
    return 0;
}
