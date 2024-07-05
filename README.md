#include <iostream>
#include <string>

void printPoem() {
    std::string poem = 
        "In the quiet of midnight,\n"
        "Solitude whispers its secrets,\n"
        "Stars flicker like ancient embers,\n"
        "And the moon, a silent sentinel.\n"
        "\n"
        "Loneliness and peace intertwine,\n"
        "In the dance of shadows and light,\n"
        "A tranquil symphony of silence,\n"
        "In the heart of the night.\n";

    std::cout << poem << std::endl;
}

int main() {
    printPoem();
    return 0;
}
