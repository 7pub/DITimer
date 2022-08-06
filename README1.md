== timer-webapp

image:https://github.com/7pub/timer-webapp/workflows/Build%20&%20Deploy/badge.svg[Build
& Deploy, link="https://github.com/7pub/timer-webapp/actions"]

image:https://img.shields.io/lgtm/grade/javascript/github/7pub/timer-webapp[LGTM
Grade, link="https://lgtm.com/projects/g/7pub/timer-webapp"]

=== Demo
https://7pub.github.io/timer-webapp

=== Screenshot
image:docs/Screenshot.png[width=100%, link="https://7pub.github.io/timer-webapp"]

=== Docker Instructions

    # initial setup
    docker build -t 7pub/timer-webapp https://github.com/7pub/timer-webapp.git
    # start the service
    docker run --rm -p 8080:80 7pub/timer-webapp
    # open the app in your browser
    xdg-open "http://localhost:8080"
