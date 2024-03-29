## P01 - Quizzler w/ FASTAPI

### Angel Badillo

### Description:

This is a simple quiz app that asks the user a series of true/false questions.
A "QuizControl" object is used to retrieve data from the FASTAPI created in the Python module, "api.py".

### Files

| # | File                                                        | Description                                     |
| :-: | ----------------------------------------------------------- | ----------------------------------------------- |
| 1 | [api.py](api.py)                                               | The FASTAPI controls the data for the quiz app. |
| 2 | [questions.json](questions.json)                               | JSON file containing data for the quiz app.     |
| 3 | [Quizzler App](https://github.com/It-Is-Legend27/P01_Quizzler) | The Flutter App, Quizzler, a quiz app.          |

### Instructions

- Go to the Github repo to download the Flutter App, Quizzler.
- Run api.py on your local machine. Ensure questions.json is
  in the same folder when you run it.
- After you have the API running, open the Flutter app in Android Studio and get all the dependencies, then run the Flutter app, and the rest is straightforward, simply complete the quiz.
- Example Command:

  - For running the API:
    - cd (folder containing both api.py and questions.json)
    - python api.py
