# q-audio-mixer
Entry to QCHack 2021, a quantum state controlled audio mixer

The project involves setting up a audio mixer that is controlled by the states generated by a quantum circuit.


### Dependencies
``` pip install pydub ```

### Instructions for use

After setting up the repository, make a folder named ``` sounds ``` to store audio clips to be mixed in the ```wav``` file format.

run the ```Q-audio-mixer.ipynb``` file using the jupyter notebook.

under the ```create_control_circuit()``` method, the space for creating a circuit has been clearly designated. The circuit is run on a statevector simulator and the output is stored as ```output.wav```

working only in linux at the moment (sadly)
