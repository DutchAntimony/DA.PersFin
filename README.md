# DA.PersFin

Financieel overzicht voor DutchAntimony

## Concept

Elk jaar wordt budget opgesteld met verwachte uitgaven per begrotingspost.
Daadwerkelijke uitgaven worden bijgehouden via bank afschrift invoer en opgesplitst per post.
Daarnaast wordt er maandelijks geld gereserveerd voor grotere uitgaven.
In deze applicatie wordt de invoer gedaan en het overzicht van uitgeven per post weergegeven.

## Technieken

SQLite database voor data opslag
Dapper als MicroORM voor communicatie tussen app en db
VSA (Vertical Slice Architecture) voor overzicht tussen de use cases
FluentValidation voor datainvoer validatie
WPF als frontend framework
XUnit voor testen van business logic (doel: 100% coverage van backend)
DA.Option en DA.Result voor verwerking van optionele data en resultaten.

