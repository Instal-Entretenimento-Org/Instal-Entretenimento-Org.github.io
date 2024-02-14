      Git Commit Standardization for Games Development body { font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; } h1 { color: #333; } h2 { color: #666; } p { color: #444; } pre { background-color: #f4f4f4; padding: 10px; border-radius: 5px; }

Git Commit Standardization for Games Development
================================================

Introduction
------------

This document defines guidelines and conventions for writing commit messages in game development repositories. The main objective is to make the commit history organized and easy to read to facilitate collaboration between development teams and improve code optimization over time.

Commit Message Structure
------------------------

    <scope (optional)> <type> - <title>
    <description>
  

Types of Commits
----------------

*   **PLAY:** Used for versioning gameplay alterations.
*   **GUI:** Used for creating, altering, or changing user interface elements.
*   **ENGINE:** Used for backend changes, including code optimizations.
*   **TEST:** Used for test alterations.
*   **RESOURCE (RESO):** Used when adding a new resource or library to the project.
*   **DOCS:** Used for upgrading documentation within the repository.
*   **CONFIG (CONF):** Used for configuring project settings.
*   **DATAUPDATE (DATUP):** Used for inserting data into the game.
*   **BUILD:** Used for alterations to prepare for building the project.

Type of Scope Additions
-----------------------

Custom scopes can be added to modify the commit context. The default commit without a scope is considered a feature commit. Additional types include:

*   **FIX:** Used for commits fixing a problem.
*   **STYLE:** Used for reorganizing without fixing a problem.
*   **REFACT:** Used for alterations aimed at optimizing the application.

Commit Message Optimization
---------------------------

Commits should be separated by type rather than combining changes into a single commit. Avoid unnecessary repetition in commit messages.

Example Commit Messages
-----------------------

    PLAY Player Movement - Add a sample script of the player’s movement.

    GUI Main Menu - Create the main menu interface.

    ENGINE Code Optimization - Improve performance by refactoring code.

    TEST Enemy Behavior - Test enemy behavior in different scenarios.

    RESOURCE Character Model - Add a new character model to the game.

    DOCS Update README - Update the project's README file with new information.

    CONFIG Audio Settings - Adjust audio settings for better sound quality.

    DATAUPDATE Level Data - Insert level data into the game.

    BUILD Version 1.0 - Prepare for the release of version 1.0.
