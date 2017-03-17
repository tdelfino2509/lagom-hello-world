How to generate a project like this

1. Ensure JDK 8 (or above) is installed:
    - http://www.oracle.com/technetwork/java/javase/downloads/index.html
1. Install Homebrew (if not already installed)
    - `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
1. Install scala and sbt:
    - `brew upgrade && brew install scala sbt`
1. Generate project with sbt from template:
    - `sbt new lagom/lagom-scala.g8`
1. Switch to project directory and run system:
    - `sbt runAll`
1. Project is running on port 9000