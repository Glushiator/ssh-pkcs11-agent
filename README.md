## Simple ssh agent with support for PKCS#11 tokens

Cloned from https://gist.github.com/tiran/c79b0ddf2d2532225cc97fc370b56dd3

    org.wikimedia.ssh-pkcs11-agent.plist -> ~/Library/LaunchAgents
    OPENSC_LIBS=/usr/local/Cellar/opensc/0.15.0/lib
    ssh-add -s $OPENSC_LIBS/opensc-pkcs11.so

