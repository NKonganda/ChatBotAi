# ChatBotAi
Add file called std-startup.xml with the code:

<aiml version="1.0.1" encoding="UTF-8">
    <!-- std-startup.xml -->

    <!-- Category is an atomic AIML unit -->
    <category>

        <!-- Pattern to match in user input -->
        <!-- If user enters "LOAD AIML B" -->
        <pattern>LOAD AIML B</pattern>

        <!-- Template is the response to the pattern -->
        <!-- This learn an aiml file -->
        <template>
            <learn>./aiml/*/*</learn>
            <!-- All aiml files are relative to the run dir and must be subdirs,
                 E.g. ./aiml/alice/one.aiml, ./aiml/custom/mine.aiml -->

        </template>

    </category>

</aiml>
