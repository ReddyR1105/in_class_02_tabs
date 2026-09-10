# Het's Notes

## 1. Widget Tree
My widget tree is `MaterialApp → Scaffold → Column → TabBar/TabBarView → tab content`. If I added a fifth tab, I would first change the `TabController` length because it controls how many tabs the app expects.

## 2. Stateless vs. Stateful
The main tab screen is stateful because it uses a `TabController`, while the tab content can be stateless because it mainly displays information. Switching them would either break the controller behavior or add unnecessary complexity.

## 3. Controllers & Lifecycle
If `_tabController.dispose()` is not called, the controller may stay in memory after the screen is closed. Over time this can waste memory, which is why a code reviewer would flag it.

## 4. Declarative UI
Flutter is declarative because I change the state and Flutter rebuilds the UI automatically. I think this is easier for a large team because developers do not have to manually update every UI element.

## 5. GitHub Teamwork
The hardest part for me was making sure I was working on my own branch instead of `main`. At a new job, I would ask about the team's Git workflow and branch naming rules before making changes.