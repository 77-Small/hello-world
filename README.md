# hello-world
first project

    public String register() {
        if (userName != null) {
            userService.register(userName, userPass);
            return "login";
        }
        return "register";

    }
