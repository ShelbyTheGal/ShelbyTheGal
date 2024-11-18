#include <iostream>
#include <string>

class User {
private:
    std::string name;
    std::string interests;
    std::string style;
    std::string description;

public:
    User(std::string userName, std::string userInterests, std::string userStyle, std::string userDescription)
        : name(userName), interests(userInterests), style(userStyle), description(userDescription) {}


};

int main() {
    User ShelbyTheGal(
        "ShelbyTheGal",
        "Building robots, programming, science, math",
        "I wish I wasn't such a nerd",
        "I like building funny stuff."
    );

}
