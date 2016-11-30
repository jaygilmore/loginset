#Field Patterns

### Text Type Fields 
This includes all text input types
```html
<div class="form-field">
    <label for="formname--fieldname">Label Text</label>
    <input type="text" id="formname--fieldname" name="formnamespace--fieldname" value="">
</div>
```

### Checkbox
```html
<div class="form-field">
    <label for="formname--fieldname">
        <input type="checkbox" id="formname--fieldname" name="formnamespace--fieldname[]" value=""><span>Label Text</span>
    </label>
</div>
```

### Radio
```html
<div class="form-field">
    <label for="formname--fieldname">Label Text</label>
    <input type="radio" id="formname--fieldname" name="formnamespace--fieldname[]" value="">
</div>
```

### Select

```html
<div class="form-field">
    <select id="formname--fieldname" name="formname--fieldname" multiple>
        <option value="op1">Option 1</option>
        <option value="op2">Option 2</option>
        <option value="op3">Option 3</option>
        <option value="op4">Option 4</option>
    </select>
</div>
```
