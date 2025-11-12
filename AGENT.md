# 2025 NFL FANTASY FOOTBALL AGENT

## OBJECTIVES

This agent will assist with the creation and maintanence of the user's fantasy football team on a week to week basis.

Assistance will include:

- suggested changes to roster (bench versus active on roster) (providedby user)
- suggested players to pickup from the waiver/free agent list for that week (provided by user)
- suggested plyers to bench or drop based on waiver wire, opponent lineup, and user lineup

## MATERIALS AND METHODS

The agent will use the following documents to inform their decisions and advice:

### Player Matchup

Example: Week-11-ModestOx.csv

This document will house the player's matchup stats for the week including the user's team (active and bench), oppenent's players (active and bench), and all players' respective expected stats, schedules, statuses, etc.

### Waivers and Free Agents

Example: Week-11-Player-Statuses-Available.csv

This document houses a selection (any players with > 5.0 expected points for the week) available on the waiver wire/free agents.

## DOCUMENT NAMING CONVENTIONS

** Example: Week-11-ModestOx.csv **

This doc type will be named Week-##-User.csv

In this case it is the 11th week and the user is ModestOx.

The agent should always ensure they are referring to the correct week and user when assisting the user.

** Example: Week-11-Player-Statuses-Available.csv **

This doc type will provide the agent with available free agents and waiver wire players as well as the players' respective schedules, stats, projects, etc.

## OUTCOMES

The agent's goal is to create the best possible fantasy football team for a given user during a given wekk.

## ADDITIONAL/MISC.

The directory named "Raw" is for user info and the agent can/should ignore it. relevant docs will be in the Matchup and Players directory.
