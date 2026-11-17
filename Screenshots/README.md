Debugging i IntelliJ IDEA

Jeg har brugt IntelliJ IDEAs debugger til at finde og rette tre fejl i Battleship-programmet.

Jeg brugte breakpoints til at stoppe programmet ved de relevante kodelinjer.

Med Step Into undersøgte jeg, hvordan metoderne blev udført.

Jeg brugte Variables-vinduet til at undersøge variablernes værdier.

Med Evaluate Expression undersøgte jeg betingelser og udtryk i koden.

Den første fejl skyldtes, at programmet kun kunne vælge vandret placering af skibe.

Den anden fejl skyldtes en forkert sammenligning i metoden isSunk().

Den tredje fejl fandt jeg med et Exception Breakpoint, som viste, at programmet forsøgte at tilgå et indeks uden for arrayets grænser.

Efter rettelserne testede jeg programmet igen for at kontrollere, at fejlene var løst.