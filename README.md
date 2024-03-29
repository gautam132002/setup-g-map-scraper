# Documentation: Running the Application

To run the application, follow these steps:

1. **Navigate to Code Folder**:
   Open the folder where all the code files are present.

2. **Open Terminal in the Folder**:
   On macOS, you can open Terminal inside the folder by following these steps:
   - Open the folder containing the code files.
   - Right-click anywhere inside the folder.
   - From the context menu, select "New Terminal at Folder" option.

3. **Execute the Command**:
   Once the Terminal is opened in the desired folder, type the following command:
   ```
   python interface.py
   ```
   Hit Enter to execute the command.

4. **Application Startup**:
   If the application starts successfully, it indicates that the setup was correct.

5. **Input Parameters**:
   The application will prompt you to input various parameters. Some of these parameters include:
   - Number of Scrolls: This parameter determines the number of times the application will scroll while fetching links. A higher value will fetch more data but will also take more time. Recommended range: 100-200.
   - Output File Name: Provide a unique name for the output file. Include either .csv or .xlsx at the end of the name. For example: `example.csv` or `example.xlsx`. This file will be generated with the fetched data.

6. **Output File Location**:
   Once the processing is complete, the output CSV or Excel file will be generated inside the folder where the code is present.

7. **Move Output File (Optional)**:
   After the processing is done, it is recommended to move the output CSV or Excel file outside the folder. This step is not compulsory but helps in keeping things organized.

8. **Running on iMac**:
   To run the application on an iMac, follow similar steps as mentioned above:
   1. Open the folder containing the code files.
   2. Open Terminal inside the folder.
   3. Root the Terminal by typing:
      ```
      sudo su
      ```
      Hit Enter.
   4. Enter your password when prompted and hit Enter again.
   5. Finally, type:
      ```
      python interface.py
      ```
      Hit Enter to execute the command.

By following these steps, you should be able to run the application successfully on your system.
