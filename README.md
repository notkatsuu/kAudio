# kMusicPlayer

kMusicPlayer is a visual music player built with C and Raylib. It provides a simple visual interface for playing your favorite music tracks.
The target of this project is developing a software to be able to enjoy music also in a visual way.w

<p align="center">
  <img src="images/demo.gif" alt="Main Interface of kMusicPlayer" width="400">
  <br>
  <i style="font-size: 12px;">kMusicPlayer Interface</i>
</p>

## Features

- **Music Playback**: Play your favorite tracks with ease. Supports `.mp3` and `.wav` formats.
- **Waveform Visualization**: Visualize your music with waveform rendering.
- **Threaded Music Loading**: Load your music in the background without interrupting your workflow.

## How to Use

### 1. **Load Music**: 
#### Use the file dialog to select your music directory. kMusicPlayer will automatically load all `.mp3` and `.wav` files in the directory.

### 2. **Control Playback**: 
#### Use the playback controls to play, pause, and skip tracks. You can also seek through the current track by clicking on the waveform.

### 3. **View Waveform**: 
#### The waveform of the current track is displayed in the main window. It updates in real-time as the track plays.
![Waveform Visualization](images/waveform.png "Waveform Visualization")
<p align="center" style="font-size: 12px;"><i>Frank Sinatra's Come Fly With Me</i></p>


## Building from Source

kMusicPlayer uses CMake for its build system. To build from source, follow these steps:

1. Clone the repository: `git clone https://github.com/your_username/kMusicPlayer.git`
2. Navigate to the project directory: `cd kMusicPlayer`
3. Create a build directory and navigate to it: `mkdir build && cd build`
4. Run CMake to generate the build files: `cmake ..`
5. Build the project: `cmake --build .`

## License


This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License. See the `LICENSE` file for details.
