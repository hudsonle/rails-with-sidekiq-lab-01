# Long-Running Tasks Lab 01

## Objectives

1. Create a long-running task.
2. Upload and process a CSV file to create songs.

## Overview
In this lab, we're going to augment the song library so that we can upload a CSV of songs and artists to expand our collection.

You will find CSV of a classic rock songs and artists in ```db/songs.csv```.

## Instructions

1. Update the songs index page to allow a CSV file upload of songs with artist name. In ```SongsController``` and action ```upload``` creates ```Song``` and ```Artist``` records from the CSV file. And redirect to songs index page.
2. Make sure tests pass using RSpec.