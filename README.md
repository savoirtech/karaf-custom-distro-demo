# Apache Karaf custom distribution demo:

This repo illustrates how one can build their own Custom Apache Karaf distribution.

## Build

To build the custom distribution, you'll need to have Maven and Java set in your environment, then run the Maven command:

```text
mvn clean install
```

When the build is complete you'll find cool-beans-core-platform-1.0.0-SNAPSHOT.tar.gz in the cool-beans-core-platform/target folder (use Zip file if on windows).

Copy this archive to a folder and extract its contents.

To start the distribution, enter it's bin folder and start Karaf.

```text
_________               .__    __________
\_   ___ \  ____   ____ |  |   \______   \ ____ _____    ____   ______
/    \  \/ /  _ \ /  _ \|  |    |    |  _// __ \\__  \  /    \ /  ___/
\     \___(  <_> |  <_> )  |__  |    |   \  ___/ / __ \|   |  \\___ \
 \______  /\____/ \____/|____/  |______  /\___  >____  /___|  /____  >
        \/                             \/     \/     \/     \/     \/

                   Cool Beans Platform                          
                  (version 1.0.0-SNAPSHOT)

Hit '<tab>' for a list of available commands
and '[cmd] --help' for help on a specific command.
Hit '<ctrl-d>' or 'shutdown' to shutdown


karaf@root()>
```
