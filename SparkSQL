 spark.sql("SELECT * FROM parquet. `/loudacre/people.parquet;`
	WHERE firstName LIKE 'A%' ").
	 show()



____________________________________________________________________________________________________________________________________________________


spark.read.load("/loudacre/people.parquet").
    select("firstName", "lastName").
    createTempView("user_name")

 spark.sql(
       "SELECT  * FROM user_names WHERE firstName LIKE 'A%'").
 show() 



____________________________________________________________________________________________________________________________________________________


val nameAgeDF = usersDF.select("name", "age")
val nameAgeover20DF = nameAgeDF.where("age > 20")
	nameAgeovfer20DF.show

	usersDF.select("name","age").where("age > 20").show


___________________________________________________________________________________________________________________________________________________









