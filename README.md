**Intezer Analyze Ghidra Plugin**
Run the plugin in Ghidra to save yourself time while reversing.
The plugin helps you focus on the malicious and unique functions.
For more information about the plugin visit our blog: 
https://www.intezer.com/blog/intezer-analyze/community-ghidra-plugin-is-here/

![alt text](https://github.com/intezer/analyze-community-ghidra-plugin/blob/master/media/ghidra_community.gif)

**Installation**
1. Clone the repo.

    ```
    $ git clone https://github.com/intezer/analyze-community-ghidra-plugin.git
    ```  
    
1. Add your API key to the environment variables: create a new variable called INTEZER_API_KEY with your API key value.
2. In Ghidra: add the path of the repo, into the list of directories that Ghidra uses for its scripts.
3. Upload the sample to https://analyze.intezer.com.
4. In Ghidra: Run the python script by double-clicking on it.
