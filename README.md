# models
1,2,3,4 model are updated with the necessary documentation.Read the codes in the ipynb file for the full understanding
*----------------------------Update-----------------------------*
1.Please change the following code from
master_df.to_json(r'C:/Users/hp/Desktop/Final/2.QB_Course_Modules_Based_Assignment_Model/'+id1+'cmb.json')(old)
to this
master_df.to_json(r"C:/Users/hp/Desktop/Final/2.QB_Course_Modules_Based_Assignment_Model/"+id1+"cmb.json")(new)
Only change single quotes to double quotes for dynamic id generation for all the models
2.Please add questions.json and QB_Skill_Based_Test.py (or ipynb) to model1 for reading of the dataset instead of the csv file,but from the json file.Code has also been changed slightly
