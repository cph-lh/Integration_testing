## Integration testing

#### Test klassen for opgaven kan findes [her](https://github.com/cph-lh/Integration_testing/blob/master/Glarmester_solution/test/glarmester_solution/data/TopDownTest.java).
Opgaven er lavet i samarbejde med Michael Daugbjerg.

- Test Metode: Vi har valgt at lave en top down test og bruge databasen som en slags dummy, da den indeholder meget lidt information.
Vi tester derfor på modulerne `DataAccessorDatabase` og `DBConnector`. Top down vil sige, at vi tester fra de øvre lag som accessoren og connecteren
og vi har derfor mulighed for at stubbe databasen, som gør det muligt at teste dette.

- Manuel eller automated testing?: Vi valgte at bruge manuel testing eftersom at testene kun skulle passe én gang.
Vi følgte ikke det var nødvendigt at skulle sætte det op med automated tools.

- Test cases:
![Test cases](https://github.com/cph-lh/Integration_testing/blob/master/test%20cases.png)




![Test results](https://github.com/cph-lh/Integration_testing/blob/master/Glarmester_solution/TestResults.PNG)
