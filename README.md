# spotify_rsm
Team repo for DSI BRS Assignment
## Table of Contents
* [General Info] (#general-info)
* [Technologies] (#technologies)
* [Setup] (#setup)
* [Inspiration] 

## General Info
This project is a simple function to generate different sorts of graphs to analyze Spotify Playlists based on any variable you'd like. We suggest to explore danceability, speechiness and valence.

#Technologies
Project is created with:
* Python version : 3.11.5
* Bash Command
* Ntfy.sh
* Among others

## Setup 
To access a Spotify API yourself, you'll need to create an account to obtain a client_id and client_secret.
To run this project you will need to generate  install it by running the following code on Colab. This did not fully work, 
and is a work in progress as google colab takes the config files away even AFTER they are packaged with the file.
Remote installing on terminal works. 

```
!pip install git+https://github.com/user/yourteamrepo
from yourteamrepo import Analysis

analysis_obj = Analysis.Analysis('config.yml')
analysis_obj.load_data()

analysis_output = analysis_obj.compute_analysis()
print(analysis_output)

analysis_figure = analysis_obj.plot_data()
```
Alternatively, from setuptools import setup

```
setup(
   name='spotify_rsm'
   version='1.1.0'
   author='Ramin, Sonia, Melissa' # hence the RSM
   packages=['spotify_rsm'])
```
## Inspiration
This repo is based on items learned during Building Software section of cohort 2 of DSI. 
Inspired by Simeon Wong, who inadvertantly taught us to push ourselves forward and read a lot of documentation on the way.
