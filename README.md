{
  "cells": [
    {
      "cell_type": "markdown",
      "id": "ecdfdfe3",
      "metadata": {},
      "source": [
        "# TITANIC-EDA"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "fd161222",
      "metadata": {},
      "source": [
        "Dataset https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv\n",
        "\n",
        "At this time, I will try to do Data Preprocessing first so that the data becomes clean and good to use. After the Data Preprocessing is done, Exploratory Data Analysis is carried out which will get useful insights, including:\n",
        "> - How many passengers are still alive?\n",
        "> - What gender is the most victimized?\n",
        "> - What age has survived the most?\n",
        "> - Is the passenger class aware of safety?"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "5d49521b",
      "metadata": {},
      "source": [
        "## DESCRIPTION"
      ]
    },
    {
      "cell_type": "markdown",
      "id": "dff2bae8",
      "metadata": {},
      "source": [
        "> Input Variable\n",
        "- pclass\tTicket class\t1 = 1st, 2 = 2nd, 3 = 3rd\n",
        "- sex\tSex\t\n",
        "- Age\tAge in years\t\n",
        "- sibsp\t# of siblings / spouses aboard the Titanic\t\n",
        "- parch\t# of parents / children aboard the Titanic\t\n",
        "- ticket\tTicket number\t\n",
        "- fare\tPassenger fare\t\n",
        "- cabin\tCabin number\t\n",
        "\n",
        "> Output Variable\n",
        "- survival - Survival\t0 = No, 1 = Yes\n",
        "\n",
        "> Variable Notes\n",
        "\n",
        "> pclass: A proxy for socio-economic status (SES)\n",
        "- 1st = Upper\n",
        "- 2nd = Middle\n",
        "- 3rd = Lower\n",
        "\n",
        "> age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5\n",
        "\n",
        "> sibsp: The dataset defines family relations in this way...\n",
        "- Sibling = brother, sister, stepbrother, stepsister\n",
        "- Spouse = husband, wife (mistresses and fiancés were ignored)\n",
        "\n",
        "> parch: The dataset defines family relations in this way...\n",
        "- Parent = mother, father\n",
        "- Child = daughter, son, stepdaughter, stepson\n",
        "- Some children travelled only with a nanny, therefore parch=0 for them."
      ]
    }
  ],
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "display_name": "Python 3.9.12 ('base')",
      "language": "python",
      "name": "python3"
    },
    "language_info": {
      "codemirror_mode": {
        "name": "ipython",
        "version": 3
      },
      "file_extension": ".py",
      "mimetype": "text/x-python",
      "name": "python",
      "nbconvert_exporter": "python",
      "pygments_lexer": "ipython3",
      "version": "3.9.12"
    },
    "vscode": {
      "interpreter": {
        "hash": "acd7da78c62dba4006ec5b78c525e9586061c13b5b0c403f449a69ff28dd52ce"
      }
    }
  },
  "nbformat": 4,
  "nbformat_minor": 5
}
