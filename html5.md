# HTML

# Forms

```html
<label for="name"> Name:
    <input type="text" name="" id="name" placeholder="Your name">
</label>
```

*Form controls are created inside the `<form>` tag.*

*The label text is the name that will be visible before the input.*

*The placeholder shows the word typed inside it in the box.*

```html
<fieldset>
    <legend>Pick One Device</legend>
    <label for="phone">
        <input type="radio" name="device" id="phone">Phone
    </label>
    <label for="TV">
        <input type="radio" name="device" id="TV">TV
    </label>
    <label for="Laptop">
        <input type="radio" name="device" id="Laptop">Laptop
    </label>
</fieldset>
```

1. `<fieldset>` creates a box around the form controls.
2. `<legend>` prints the text written inside it on the box created by the fieldset.

# Table

```html
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
```

1. `<tr>` represents a table row. It creates a row in the table.
2. `<td>` is table data. It inserts data inside the table row.
3. `colspan="4"` means the cell spans 4 columns.

## Copyright symbol

Write `&copy;` in HTML to show the © symbol.