Learn MySQL
-----
1. Go to the MySQL download site

        https://dev.mysql.com/downloads/file/?id=486089

    Click on the following line to start the download 

        No thanks, just start my download.

2. You should have downloaded `mysql-installer-community-8.0.16.0.msi`, run the installer.

    Follow the instructions in the installer. When given a choice for the setup type, choose, `Developer Default`.

    If the setup says that some requirements are not met (e.g. Visual Studio and Python), it is ok to continue with `Next`. Finally, click `Execute` to start the installation.

    After the installation, you will follow a series of steps to configure MySQL Server. Click `Next` untill it requires you to set a MySQL root password. Please note down this password. You will be asked again to `check` this password at the end of the setup.

    Continue through the configuration and click `Execute` at the end to begin the automatic configuration, click `Finish`. 

3. The setup should launch `MySQL Workbench` afterwards.

    Under `MySQL Connections`, select your `Local Instance`. You might be asked for your root password.

4. On the `Navigator` panel on the left hand side of the window, click the `Schemas` tab.

    Create a new schema by right clicking and choosing `Create Schema...`.

    Choose a name for your schema and click `Apply` and then `Apply`. You should see your new schema in the `Schema` tab.

5. Expand your schema (arrow on the left), under `Tables`, right click and `Create Table...`.

    