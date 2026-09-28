# HTML

# Forms


        <label for="name"> Name:
           <input type="text" name="" id="name" placeholder="Your name">
        </label>


*form will be created insige form tag.* 

*label name will be the name that will be visible before input type.*

*Placeholder will show the word in the box that is typed inside the place holder*



        <fieldset>
            <legend>Pick One Device</legend>
            <label for="Phone">
                <input type="radio" name="device" id="phone">Phone
            </label>
            <label for="TV">
                <input type="radio" name="device" id="TV">TV
            </label>
            <label for="Laptop">
                <input type="radio" name="device" id="Laptop">Laptop
            </label>
        </fieldset>


1. Fieldset create a box over the form
2. Legend will print the string written inside it inside the box that has been created by the fieldset

# Table

<table>
    <thead>
       <tr>
        <td colspan="4">Employee Info</td>
       </tr>
    </thead>

    <tbody>
        <tr>
            <td>No.</td>
            <td>Full Name</td>
            <td>Position</td>
            <td>Salary</td>
        </tr>

        <tr>
            <td>1</td>
            <td>Bill Gates</td>
            <td>Founder Microsoft</td>
            <td>$1000</td>
        </tr>

        <tr>
            <td>2</td>
            <td>Steve Jobs</td>
            <td>Founder Apple</td>
            <td>$1200</td>
        </tr>

        <tr>
            <td>3</td>
            <td>Larry Page</td>
            <td>Founder Google</td>
            <td>$1100</td>
        </tr>

        <tr>
            <td>4</td>
            <td>Mark Zuckerberg</td>
            <td>Founder Facebook</td>
            <td>$1300</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td colspan="4">Number of Employees: 4</td>
         </tr>
    </tfoot>
   </table>

   1. <tr> represents table row. It will create a row in the table

   2. <td> it is table data, it will insert data inside the table row.

   3. colspan="4" represents that the row will be 4 columns long.

   ## **@copy! is the command to create copyright symbol**