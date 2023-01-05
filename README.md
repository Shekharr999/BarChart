{
  "formName": "Dynamic Form",
  "fileName":"demo.js",
  "apiUrl":"users",
  "FormFileds": [
      {
          "type": "text",
          "name": "firstName",
          "label": "First Name",
          "validationRequired":true,
          "validationMessage":"LastName required"
      },
      {
          "type": "text",
          "name": "lastName",
          "label": "Last Name",
          "validationRequired":true,
          "validationMessage":"LastName required"
      },
      {
          "type": "email",
          "name": "email",
          "label": "Email",
          "validationRequired":true,
          "validationMessage":"Email required"
      },
      {
          "type": "password",
          "name": "password",
          "label": "Password",
          "validationRequired":true,
          "validationMessage":"Password required"
      },
      {
          "type": "number",
          "name": "number",
          "label": "Phone Number",
          "validationRequired":true,
          "validationMessage":"Phone Number required"
      },
      {
          "type": "radio",
          "label": "Gender",
          "name": "gender",
          "options": [
              "Don't Confirm",
              "Female",
              "Male"
          ],
          "validationRequired":true,
          "validationMessage":"Gender required"
      },
      {
          "type": "checkbox",
          "label": "Skills",
          "name": "skills",
          "options": [
              "Frontend",
              "Backend",
              "Full Stack"
          ],
          "validationRequired":true,
          "validationMessage":"Skills required"
      },
      {
          "type": "dropdown",
          "name": "region",
          "label": "Region",
          "validationRequired":true,
          "validationMessage":"Region required"
      },
      {
          "type": "file",
          "name": "file",
          "label": "File",
          "validationRequired":true,
          "validationMessage":"File required"
      }
  ]
}
