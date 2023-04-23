
# SteelEye Python Engineer Assignment

## Implementation :

(i) Download the XML file

(ii) Download the .zip folders

(iii) Extract the xml from the zip

(iv) Convert the contents of the xml into a CSV with the following header:
- FinInstrmGnlAttrbts.Id
- FinInstrmGnlAttrbts.FullNm
- FinInstrmGnlAttrbts.ClssfctnTp
- FinInstrmGnlAttrbts.
- CmmdtyDerivInd
- FinInstrmGnlAttrbts.NtnlCcy
- Issr

(v) Storing the csv from step (iv) in an AWS S3 bucket

## Upload to AWS S3 Bucket

<img width="900" alt="Screenshot 2023-04-23 at 6 03 54 PM" src="https://user-images.githubusercontent.com/73490217/233855263-f77915c3-99b9-423a-a8e5-c27ce09e2af1.png">





## How to Run

- Open your Terminal or Powershell

- Clone the Repository or Download the .zip file

```bash
  git clone https://github.com/abantika001/AbantikaChandra_PythonAssignment
```

- Use Jupyter Notebook or VS Code

- Create a folder named "Data" inside the Cloned folder (Make sure you don't put the .ipynb file inside the "Data" folder)

- Create a bucket in AWS S3 named "steeleyedataengineer"

- Now create a access key 

- Change the values of Access ID and Secret Access Key in the code 

- Run the .ipynb file

Note : In case you have not created the AWS S3 bucket, the last cell of code will throw an error.
