# Serialization
Serialization is the process of converting an object into a stream of bytes to store the object or transmit it to memory, a database, or a file. Its main purpose is to save the state of an object in order to be able to recreate it when needed. The reverse process is called deserialization
- https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/serialization/

# Pickle
Pickle is a module that serializes and de-serializes Python objects.

# JobLib
JobLib is a module that serializes and de-serializes Python objects, and it's even more efficient than Pickle for numpy Arrays.
- Useful for SKLearn models or Panda DataFrames

### Installation
Use ```pip install joblib``` or ```conda install -c anaconda joblib``` if using Anaconda.

# Documentation
- https://docs.python.org/3/library/pickle.html