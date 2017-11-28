Redbox Digital

Installing

By GIT:

clone this repo
disable compilation if you use that.
copy the files from the repo into the base folder of your magento install
clear your cache
re-enable compilation


Un-Installing

By Manually:

Open file from app/etc/modules/RedboxDigital_Linkedin.xml and make the changes like below
    <config>
        <modules>
            <RedboxDigital_Linkedin>
                <active>false</active>
                <codePool>community</codePool>
            </RedboxDigital_Linkedin>
        </modules>
    </config>
