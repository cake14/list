
<style>
* {box-sizing: border-box}

/* Add padding to containers */
.container {
  padding: 16px;
}

/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

/* Overwrite default styles of hr */
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

/* Set a style for the submit/register button */
.registerbtn {
  background-color: #4CAF50;
  color: white;
  padding: 16px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

.registerbtn:hover {
  opacity:1;
}

/* Add a blue text color to links */
a {
  color: dodgerblue;
}

/* Set a grey background color and center the text of the "sign in" section */
.signin {
  background-color: #f1f1f1;
  text-align: center;
}
.error{
	color:red;
}
label{
	{
    break-after: auto;
}
}
</style>



<form action='' method='post' class='myform' id='myform' data-route="{{ route('postData') }}">
  <div class="container">
    <h1>Register</h1>
    <hr>

    <input type="text" placeholder="Name" name="name">

    <input type="text" placeholder="Enter Email" name="email">

    <input type="password" placeholder="Enter Password" name="password">

    <input type="password" placeholder="Repeat Password" name="cpassword">
	
	 <input type="text" placeholder="Phone Number" name="phone">
	
	<br><br>
	<input type="radio" placeholder="" name="gender" value='male' checked > Male 
	<input type="radio" placeholder="" name="gender" value='female'> Female
    <hr>
	
	
	
	
	 Image <input type="file" placeholder="" name="image" id='image'>
	 

    <p>By creating an account you agree to our <a href="#">Terms & Privacy</a>. <input type='checkbox' name='agree'></p>
    <button type="submit" class="registerbtn">Register</button>
  </div>

</form>

<div id='message'>
	</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
<script src="https://ajax.aspnetcdn.com/ajax/jquery.validate/1.11.0/jquery.validate.min.js"></script>

<script>
$(document).ready(function () {	
    
    $(".site_header").addClass("inner_page_header");

	$('#myform').validate({ 
		rules: {
			name:{
				required: true,
				minlength: 7,
				maxlength: 15,
			},
			 email:{
				required: true,
				email: true
			},
			password:"required", 
			cpassword:{
				required: true,
				//equalTo: "#password"
			},
			phone:{
				required: true,
				number: true,
				minlength:7,
                maxlength:15,
			},
			gender:"required", 
			image:"required", 
			agree:"required",  
		},
		messages: {
			name: {
				required: "Enter a name",
				minlength: "Enter a 7",
				remote: "Enter a 15"
			},
        },
		submitHandler: function (form) { 
		    
		    //console.log($('#myform').serialize());
			var name ='tarun';
			var fd = new FormData(); 
			var files = $('#image')[0].files[0]; 
			 console.log(files);
			fd.append('file', files); 
			fd.append('name', name); 
			
			var route = $('#myform').data('route');
			alert(route);
		
				$.ajax({
					 url:route,
					 type:'POST',
					 data: fd,
					 processData: false,
					 contentType: false,
					 dataType :'json',
					 success:function(data){
						console.log(data);
										/* swal({
											title: "Success!",
											text: "Package Added Successfully!",
											icon: "success",
										  //  type: "success"
										}).then(function() {

											window.location = data.url;
								
										}); */
					},
					error: function() { 
					 alert("Fail");
									/* swal({
									  title: "Unsuccessfull!",
									  text: "Please Try Again.",
									  icon: "warning",
									  buttons: true,
									  dangerMode: true,
									})	 */   
				   }
				});

		
		
			   /*$.ajax({
				type: 'post',
				url: 'ajax.php',
				data: fd,
				success: function (res) {
				 
					var result = JSON.parse(res);

					//alert(result)
					 
					if(result.status =='1'){
						$('#message').html('<p class="alert alert-success">'+result.message+'</p>');
					}else{
						$('#message').html('<p class="alert alert-danger">'+result.message+'</p>');
					}
					
				}
			  });	 */
		}
	});
});
</script>
===========================================================================================================
{!! Form::open(['action'=>'PostsController@store','method'=>'POST']) !!}
{{Form::label('name','Name')}}
{{Form::text('name','',[])}}
{{Form::text('email','',[])}}
{{Form::password('password','',[])}}
{{Form::password('cpassword','',[])}}
{{Form::text('phone','',[])}}
{{Form::radio('gender', 'male' , true) }}



{{Form::submit('submit','',[])}}
{!! Form::close() !!}
===========================================================================================================


<?php 

class User extends AppModel {

    public $validate = array(
          'first_name' => array(
			'notBlank' => array(
                'rule' => 'notBlank',
                'message' => 'This field cannot be left blank'
            ),
            'alphaNumeric' => array(
                'rule' => 'alphaNumeric',
                'required' => true,
                'message' => 'Letters and numbers only'
            ),
            'between' => array(
                'rule' => array('lengthBetween', 5, 15),
                'message' => 'Between 5 to 15 characters'
            )
        ), 
        
         'email' => array(
			'notBlank' => array(
                'rule' => 'notBlank',
                'message' => 'This field cannot be left blank'
            ),
			'required' => array(
				'rule' => array('email'),
				'message' => 'Invalid Email format'
			),
			'maxLength' => array(
				'rule' => array('maxLength', 255),
				'message' => 'Email cannot be more than 255 characters.'
			),
			'unique' => array(
				'rule' => 'isUnique',
				'message' => 'Provided Email already exists.',
				'on' => 'create'
			)
		),
	 	'password' => array(
			'notBlank' => array(
                'rule' => 'notBlank',
                'message' => 'This field cannot be left blank'
            ),
			'lengthBetween' => array(
                 'rule' => array('lengthBetween', 5, 15),
                'message' => 'Between 5 to 15 characters'
            ),
 
        ),
		'password_confirm' => array(
                 'notBlank' => array(
                        'rule' => 'notBlank',
                        'message' => 'This field cannot be left blank',
                 ),
				'password_confirm'=>array(
                'rule'=>array('password_confirm'),
                'message'=>'Password Confirmation must match Password',                         
            ), 
        ), 
		
    );
	
 
	
	public function password_confirm(){ 
        if ($this->data['User']['password'] !== $this->data['User']['password_confirm']){
            return false;       
        }
        return true;
    }
		

} 

=====================================================
<?php

App::uses('AppController', 'Controller');


class UsersController extends AppController {


	public function index() {
		
		$users = $this->User->find('all',array('order'=>array('id'=>'desc')));
		$this->set('users',$users);
		return  $this->render('index');
		
	}
	
	public function add(){
		 
		if ($this->request->is('post')) {
			$this->User->create();
			$this->User->set($this->request->data);

			if ($this->User->validates()) {
				
				if(!empty($this->data['User']['upload']['name'])){
					$file = $this->data['User']['upload'];
					//move_uploaded_file($file['tmp_name'], WWW_ROOT . 'img/uploads/users/' . $file['name']);
					//$this->data['User']['image'] = $file['name'];
					
				} 
				
				
				$this->User->save($this->request->data);
				$this->Flash->success('Registered Successfully.');
				return $this->redirect(array('action' => 'index'));    
			}
		}
	}

}


============



<a href='/cdg2/cakephp/users'>List </a>

<?php

	echo $this->Form->create('User'); 
	echo $this->Form->input('first_name',array('required'=>false));  
	echo $this->Form->input('email',array('type' => 'text','required'=>false)); 
	echo $this->Form->input('password',array('required'=>false));  
	echo $this->Form->input('password_confirm',array('required'=>false)); 

	echo $this->Form->input('image', array('type' => 'file')); 
	
	echo $this->Form->input('gender', array(
        'type' => 'radio',
        'options' => array(
            '1' => 'Male',
            '2' => 'Female', 
        ),
		'value' => '1'
	));
	
	
	echo $this->Form->input('accept', array(
        'type' => 'checkbox',
        'label' => 'I accept the Terms & Conditions',
		//'required'=>true
        
	));

	echo $this->Form->submit('Register');  
	echo $this->Form->end(); 
 
 
 
 ?>





