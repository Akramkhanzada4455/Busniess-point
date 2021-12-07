# Busniess-point
<?xml version="1.0" encoding="UTF-8"?>

-<RelativeLayout tools:visibility="visible" android:visibility="visible" tools:context=".MainActivity" android:background="#ffff" android:layout_height="match_parent" android:layout_width="match_parent" android:id="@+id/username" xmlns:tools="http://schemas.android.com/tools" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:android="http://schemas.android.com/apk/res/android">

<EditText android:layout_height="wrap_content" android:layout_width="wrap_content" android:id="@+id/editTextTextPersonName3" android:text="User Name" android:inputType="textPersonName" android:ems="10" android:layout_marginBottom="161dp" android:layout_marginEnd="104dp" android:layout_alignParentEnd="true" android:layout_above="@+id/thur"/>

<TextView android:layout_height="wrap_content" android:layout_width="0dp" android:text="Hello World!" android:layout_marginEnd="411dp" android:layout_alignParentEnd="true" app:layout_constraintVertical_bias="0.39" app:layout_constraintTop_toTopOf="parent" app:layout_constraintRight_toRightOf="parent" app:layout_constraintLeft_toLeftOf="parent" app:layout_constraintBottom_toBottomOf="parent"/>

<TextView android:layout_height="wrap_content" android:layout_width="match_parent" android:id="@+id/textView" android:text="Do you hav't an Account!" android:layout_marginBottom="7dp" android:layout_above="@+id/createNow" app:layout_constraintTop_toTopOf="parent" app:layout_constraintStart_toStartOf="parent" android:textStyle="italic" android:textSize="18sp" android:fontFamily="serif" android:layout_marginTop="4dp" style="@android:style/Widget.DeviceDefault.TextView"/>

<Button android:layout_height="wrap_content" android:layout_width="wrap_content" android:id="@+id/thur" android:text="Login" android:layout_marginBottom="48dp" android:layout_marginEnd="143dp" android:layout_alignParentEnd="true" android:layout_above="@+id/createNow" android:layout_marginStart="180dp" android:layout_alignParentStart="true"/>

<Button android:background="#00FFFFFF" android:layout_height="wrap_content" android:layout_width="172dp" android:id="@+id/createNow" android:text="Create Now" android:layout_marginBottom="45dp" android:layout_marginEnd="129dp" android:layout_alignParentEnd="true" style="@style/Widget.AppCompat.Button" android:layout_marginStart="109dp" android:layout_alignParentStart="true" app:strokeColor="#D5FFFFFF" app:rippleColor="#FFFFFF" android:textColor="#6D63FD" android:textAppearance="@style/TextAppearance.AppCompat.Small" android:layout_alignParentBottom="true"/>

<ImageView android:layout_height="228dp" android:layout_width="352dp" android:id="@+id/imageView" android:layout_marginBottom="209dp" android:layout_marginEnd="36dp" android:layout_alignParentEnd="true" android:layout_above="@+id/thur" android:layout_marginStart="23dp" android:layout_alignParentStart="true" app:srcCompat="@drawable/logobg"/>

<EditText android:layout_height="wrap_content" android:layout_width="222dp" android:id="@+id/editTextTextPersonName2" android:text="Business Name" android:inputType="textPersonName" android:ems="10" android:layout_marginBottom="108dp" android:layout_marginEnd="67dp" android:layout_above="@+id/thur" android:layout_marginStart="-2dp" android:layout_alignEnd="@+id/imageView" android:layout_alignStart="@+id/editTextTextPersonName3"/>

<EditText android:layout_height="wrap_content" android:layout_width="wrap_content" android:id="@+id/editTextTextPersonName4" android:text="Phone" android:inputType="textPersonName" android:ems="10" android:layout_marginBottom="56dp" android:layout_marginEnd="103dp" android:layout_alignParentEnd="true" android:layout_above="@+id/thur" android:layout_marginStart="2dp" android:layout_alignStart="@+id/editTextTextPersonName3"/>

<EditText android:layout_height="wrap_content" android:layout_width="wrap_content" android:id="@+id/editTextTextPersonName5" android:text="Password" android:inputType="textPersonName" android:ems="10" android:layout_marginBottom="5dp" android:layout_marginEnd="-1dp" android:layout_above="@+id/thur" android:layout_marginStart="2dp" android:layout_alignEnd="@+id/editTextTextPersonName4" android:layout_alignStart="@+id/editTextTextPersonName4"/>

<TextView android:layout_height="41dp" android:layout_width="314dp" android:id="@+id/textView2" android:text="Business Point" android:layout_marginBottom="114dp" android:layout_marginEnd="85dp" android:layout_alignParentEnd="true" android:layout_above="@+id/imageView" android:textSize="34sp" style="@android:style/Widget.DeviceDefault.TextView.SpinnerItem" android:layout_marginStart="70dp" android:layout_alignParentStart="true" android:textColor="#1844E4" android:textColorLink="#FFFFFF"/>

</RelativeLayout>

<?xml version="1.0" encoding="UTF-8"?>

-<LinearLayout tools:context=".Sign_in_Activity" android:layout_height="match_parent" android:layout_width="match_parent" xmlns:tools="http://schemas.android.com/tools" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:android="http://schemas.android.com/apk/res/android">


-<LinearLayout android:layout_height="match_parent" android:layout_width="match_parent" android:orientation="vertical" android:layout_marginBottom="15dp" android:layout_marginRight="40dp" android:layout_marginTop="20dp" android:layout_marginLeft="40dp">

<ImageView android:layout_height="wrap_content" android:layout_width="match_parent" app:srcCompat="@drawable/logobg" android:id="@+id/imageView2"/>

<TextView android:layout_height="70dp" android:layout_width="match_parent" android:id="@+id/textView9" app:civ_border_color="@color/purple_700" android:textSize="40dp" android:text="Business Point" android:gravity="center"/>
/> 
<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="20dp" android:layout_marginTop="10dp" android:id="@+id/editTextPhone2" android:inputType="phone" android:hint="3054009589"/>

<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="20dp" android:id="@+id/editTextTextPassword" android:inputType="textPassword" android:hint="Enter Password"/>

<Button android:layout_height="wrap_content" android:layout_width="match_parent" android:text="Login" android:layout_gravity="center"/>


-<LinearLayout android:layout_height="100dp" android:layout_width="match_parent" android:orientation="horizontal" android:layout_marginTop="10dp">

<TextView android:layout_height="80dp" android:layout_width="wrap_content" android:layout_marginLeft="3dp" android:id="@+id/textView12" android:textSize="20dp" android:text="have't an account ?" android:textColor="@color/black"/>

<TextView android:layout_height="80dp" android:layout_width="222dp" android:textSize="20dp" android:text="Register" android:textColor="@color/purple_700"/>

</LinearLayout>

</LinearLayout>

</LinearLayout>

<?xml version="1.0" encoding="UTF-8"?>

-<RelativeLayout tools:context=".Sign_up_Activity" android:background="#fff" android:layout_height="match_parent" android:layout_width="match_parent" xmlns:tools="http://schemas.android.com/tools" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:android="http://schemas.android.com/apk/res/android">


-<LinearLayout android:layout_height="match_parent" android:layout_width="match_parent" android:orientation="vertical" android:layout_marginBottom="15dp" android:layout_marginRight="40dp" android:layout_marginTop="20dp" android:layout_marginLeft="40dp">

<de.hdodenhof.circleimageview.CircleImageView android:layout_height="100dp" android:layout_width="match_parent" xmlns:app="http://schemas.android.com/apk/res-auto" app:civ_border_color="@color/purple_700" app:civ_border_width="2dp" android:src="@drawable/images" android:id="@+id/profile_image"/>

<TextView android:layout_height="70dp" android:layout_width="match_parent" android:id="@+id/textView9" android:textSize="30dp" android:text="Upload Image" android:gravity="center"/>

<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="10dp" android:id="@+id/editTextTextPersonName7" android:inputType="textPersonName" android:hint="User Name"/>

<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="10dp" android:id="@+id/editTextTextPersonName8" android:inputType="textPersonName" android:hint="Business (machanical electriacl....)"/>

<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="10dp" android:id="@+id/editTextPhone2" android:inputType="phone" android:hint="3054009589"/>

<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="10dp" android:id="@+id/editTextTextEmailAddress" android:inputType="textEmailAddress" android:hint="example@gmail.com"/>

<EditText android:layout_height="wrap_content" android:layout_width="match_parent" android:layout_marginBottom="10dp" android:id="@+id/editTextTextPassword" android:inputType="textPassword" android:hint="Strong Password"/>

<Button android:layout_height="wrap_content" android:layout_width="match_parent" android:text="Submit" android:layout_gravity="center"/>

<TextView android:layout_height="80dp" android:layout_width="match_parent" android:layout_marginTop="10dp" android:id="@+id/textView12" android:textSize="20dp" android:text="Already Registered" android:textColor="@color/black"/>

<TextView android:layout_height="match_parent" android:layout_width="match_parent" android:textSize="20dp" android:text="Login Now" android:layout_gravity="center" android:textColor="@color/purple_700"/>

</LinearLayout>

</RelativeLayout>

<?xml version="1.0" encoding="UTF-8"?>

-<LinearLayout tools:context=".Splash_Screen_Activity" android:layout_height="match_parent" android:layout_width="match_parent" xmlns:tools="http://schemas.android.com/tools" xmlns:app="http://schemas.android.com/apk/res-auto" xmlns:android="http://schemas.android.com/apk/res/android">

<ImageView android:layout_height="match_parent" android:layout_width="match_parent" app:srcCompat="@drawable/logobg" android:layout_gravity="center" android:layout_marginBottom="30dp" android:layout_marginTop="30dp" android:layout_marginRight="30dp" android:layout_marginLeft="30dp" android:id="@+id/imageView2"/>

</LinearLayout>
