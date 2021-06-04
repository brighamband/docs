# Silver-Fund-Web-App

## Overview

An institutional-quality web app created for use by Silver Fund, The Marriott Business School's student-run investment fund. This app aims to support investment research, trading, risk management, and portfolio analysis.

> Want to learn more about the Silver Fund? Visit [our general webpage](https://silverfund.byu.edu/)!

## Web App URLs

[Production URL - 47fund.byu.edu](https://47fund.byu.edu/)

[Development URL - 47fund-dev.byu.edu](https://47fund-dev.byu.edu/)

## Documentation

#### Front-End Overview / Structure (`frontend` directory, ReactJS)

- `src` - Directory for React source code

  - `components` - Directory for react components
    - `shared` - Directory for react components that are reused throughout the project
    - Other folders contain related code that is related to a specific pane (ex: `positions` directory contains all the files that make up the Positions pane)
  - `media` - Directory for logos, images, videos, etc.
  - `utils` - Directory for helper files and constants used throughout the front-end

  > NOTE - While there is a styles.css file, we are switching to using [`styled-components`](https://styled-components.com/) for css, so add styling that way instead.

#### Back-End Overview / Structure (`backend` directory, Django Rest Framework)

- `api` - Directory for Django app
  - `ibgateway_manager` - Directory for managing connection to Interactive Brokers Gateway
  - `migrations ` - Directory containing database migration scripts (don't touch this folder unless you are having migration issues -- if that's the case you may have to delete the files containing _auto_)
    > - Use the `python manage.py makemigrations` command to auto-create a migrations script with your new changes to the database.
    > - Use the `python manage.py migrate` command to run the migrations script created in the step above.
  - `admin.py` - File for adjusting configuration of admin site (accessed at `{project_url}/admin`)
  - `models.py` - File for managing database tables (add or remove tables here, or adjust their fields)
    > NOTE - Changes won't be seen until you run the migration commands shown a few bullets above.
  - `serializers.py` = File for managing how database data gets turned into JSON for API use, and vice versa.
  - `views.py` - File containing the functionality of API endpoints (what code runs when a respective URL receives a request)
- `backend` - Directory for Django project
  - `settings.py` - File containing project configuration settings
  - `urls.py` - File containing the set of back-end URL endpoints

#### Adding New Users to Web App

> Visit [this Google Doc](https://docs.google.com/document/d/1L7HjXed0X-YRETpqLMY0JjNnpgvdBVeURnsIOBn9x3U/edit) for more step-by-step instructions on adding new users.
