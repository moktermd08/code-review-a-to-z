function login(user, pass) {
    if (user == "admin" && pass == "12345") {
        return true;
    }
    return false;
}


Review:

Security: Hardcoding credentials is insecure. Use environment variables or authentication services.
