1. to start new server 

**npm init**

2. change the package.json "script" path

change to 
"Start: " "node index.js"

3. **npm install express**

4. Go to express website and copy the sample code 

5. And Run that on 3000 port by using **npm run start**

6. make another routers/repository to route 

7. the reapeat the **npm run start**

Done

then **install i dotenv**

8. goto browser the open npm dot env
    then copy **require('dotenv').config()** copy this one and paste on index.js file on top.

9. create another file by name (.env)

    then write **PORT = 3000**

10. on script.js   

        app.listen(process.env.PORT, () => {
  console.log(`Example app listening on port ${port}`)
})

11. 