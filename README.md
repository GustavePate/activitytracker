# Activitytracker

## Goal

This python script intends to count the number of  minutes you use your computer per day.
It's based on user input activity (keyword and mouse).

Basically each minutes during which a user input event happens is considered as an active minute.
Theses actives minutes are logged in a file and a counter of theses minutes is kept.

## Installation

    git clone https://github.com/GustavePate/activitytracker
    pip install -r requirements.txt

## Usage

Specify the path where the logs will be written (format specifiedpath/YYYYMMDD_useractivitytracker.log)
Each minute associated to a user event will be logged, the total minutes of activity also.

    python tracker.py /tmp/

You'd better start this program on boot to have your whole day.

## Limitation

On program restart, the total minutes of activity will be reset.
