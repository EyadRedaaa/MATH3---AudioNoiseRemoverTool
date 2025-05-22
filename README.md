# MATH3---AudioNoiseRemoverTool


A MATLAB-based tool that applies frequency domain filtering to reduce noise in audio signals and visualize the Fourier Transform process. It provides interactive control over the filter radius, enabling users to fine-tune the balance between noise reduction and detail preservation.

Description :-

The Audio Noise Remover Tool leverages Fourier Transform techniques to process audio signals in the frequency domain. It allows applying low-pass and high-pass filters to either remove noise or extract fine details from audio. It also supports visualization of key steps: audio signal plotting, Fourier magnitude computation, and filtering results.

Features :-

Read and Plot Audio Signals: Load audio files and visualize the original noisy signal.
Fourier Transform Visualization: Compute and display the magnitude spectrum of the audio signal.
Custom Radius-based Filters: Apply low-pass and high-pass filters based on user-defined radius values to control noise reduction.
Interactive User Inputs: Allow users to specify the filter radius for custom filtering.
Inverse Fourier Transform (IFFT): Transform the filtered frequency domain back to the time domain for playback.
Playback Processed Audio: Use the sound function to play the filtered audio signal.

Tools & Technologies :-

MATLAB: Core programming language for implementation.
Audio Processing Functions: For handling audio operations like reading and playing sound.
Fast Fourier Transform (FFT): To transform audio signals into the frequency domain.
Frequency Filters: To isolate low or high-frequency components based on user-defined parameters.

