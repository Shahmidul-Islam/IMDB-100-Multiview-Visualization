# Task C: Visualisation of Movie Category, Votes, and Year

The top 99 highest rated IMDB movies are visualised in this demonstration. We display how the category of a movie affects the total votes received. In essence, this shows us how categories affect popularity and allow the user to filter the movies based on the year.

## Initial Setup

1. Install a recent version of [Python](https://www.python.org/downloads/).
2. Install [Poetry](https://python-poetry.org/docs/#installing-with-the-official-installer).
3. Navigate to the root of this directory in the terminal.
4. Run `poetry install` to install the dependencies.

## Running the Code

1. Navigate to the root of this directory in the terminal.
2. Run `poetry run mercury run` to run the code.
3. The application will be available at http://localhost:8000.

## Usage Instructions

1. The full range of years and votes is allowed by default. The sliders can be adjusted to restrict the ranges freely and the graphs will reflect the updated range. Use the sidebar on the left for this.
2. There is also a slider that changes the height of the charts.
3. Hovering over the points will show related information on tooltips.
4. The scatter plot allows rectangular selection and the bar chart allows interval selection. The brushes selectively highlight on both plots. The selection area can be moved around by dragging. The size can be changed by scrolling on the selected area.
5. Click outside the selection area to deselect and reset the plot.

Made with ❤️ by Mohammad Shahmidul Islam.