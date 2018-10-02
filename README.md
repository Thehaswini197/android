# android
<EditText
   android:id = "@+id/editText2"
   android:layout_width = "wrap_content"
   android:layout_height = "wrap_content"
   android:inputType = "textPassword" />

<EditText
   android:id = "@+id/editText1"
   android:layout_width = "wrap_content"
   android:layout_height = "wrap_content"
/>
<Button
   android:id = "@+id/button1"
   android:layout_width = "wrap_content"
   android:layout_height = "wrap_content"
   android:onClick = "login"
   android:text = "@string/Login" 
/>
EditText username = (EditText)findViewById(R.id.editText1);
EditText password = (EditText)findViewById(R.id.editText2);		

public void login(View view){
   if(username.getText().toString().equals("admin") && password.getText().toString().equals("admin")){
   
   //correcct password
   }else{
   //wrong password
}	
int counter = 3;
counter--;

if(counter==0){
   //disble the button, close the application e.t.c
}
