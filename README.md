## Screenshot

![Demo](https://raw.githubusercontent.com/amitthecoder/profile-app/main/screenshot.png "Demo")

## XML Code

```xml
<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_marginTop="10dp"
        android:padding="15dp">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="@string/profile"
            android:textStyle="bold"
            android:textSize="30sp"
            android:fontFamily="@font/poppinsbold"
            android:layout_gravity="center"
            android:textColor="@color/black"/>

        <com.google.android.material.card.MaterialCardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            app:cardCornerRadius="10dp"
            android:layout_marginTop="20dp">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="vertical"
                android:layout_marginTop="0dp"
                android:padding="15dp">

            <com.google.android.material.imageview.ShapeableImageView
                android:layout_width="150dp"
                android:layout_height="150dp"
                android:layout_gravity="center"
                android:src="@drawable/user"/>
            <LinearLayout
                android:layout_width="wrap_content"
                android:layout_height="wrap_content"
                android:layout_gravity="center"
                android:layout_marginTop="15dp"
                android:orientation="horizontal">

                <TextView
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:text="@string/amit_kumar"
                    android:textAlignment="center"
                    android:textSize="20sp"
                    android:fontFamily="@font/poppinsmedium"
                    android:textColor="@color/black"
                    android:textStyle="bold"/>

                <com.airbnb.lottie.LottieAnimationView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:layout_marginBottom="1dp"
                    android:layout_marginStart="3dp"
                    app:lottie_rawRes="@raw/verified"
                    app:lottie_autoPlay="true"
                    app:lottie_loop="true"/>

            </LinearLayout>
            </LinearLayout>

        </com.google.android.material.card.MaterialCardView>

        <com.google.android.material.card.MaterialCardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="10dp"
            app:cardCornerRadius="10dp">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="vertical"
                android:padding="15dp">
                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/about"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginTop="30dp"
                        android:textColor="@color/black"
                        android:text="@string/bio"
                        android:fontFamily="@font/poppinsregular"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true" />
                </RelativeLayout>

            </LinearLayout>

        </com.google.android.material.card.MaterialCardView>

        <com.google.android.material.card.MaterialCardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="10dp"
            app:cardCornerRadius="10dp">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="vertical"
                android:padding="15dp">

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/user_information"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp"
                    android:layout_marginTop="15dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/username_"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="#6E6C6C"
                        android:text="@string/amitthecoder"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentEnd="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="15dp"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/gender"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="#6E6C6C"
                        android:text="@string/male"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentEnd="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="15dp"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/age"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="#6E6C6C"
                        android:text="@string/_21"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentEnd="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="15dp"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/date_of_birth"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="#6E6C6C"
                        android:text="@string/_07_02_2003"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentEnd="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="15dp"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/mobile"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="#6E6C6C"
                        android:text="@string/_91_9000000009"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentEnd="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="15dp"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/email"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="#6E6C6C"
                        android:text="@string/axxxxxxa_gmail_com"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentEnd="true"
                        android:textStyle="bold"/>
                </RelativeLayout>
            </LinearLayout>

        </com.google.android.material.card.MaterialCardView>

        <com.google.android.material.card.MaterialCardView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:layout_marginTop="10dp"
            android:layout_marginBottom="30dp"
            app:cardCornerRadius="10dp">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="vertical"
                android:padding="15dp">

                <RelativeLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginStart="10dp"
                    android:layout_marginEnd="10dp">
                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:textColor="@color/black"
                        android:text="@string/social_media"
                        android:fontFamily="@font/poppinsmedium"
                        android:textSize="15sp"
                        android:layout_alignParentStart="true"
                        android:textStyle="bold"/>
                </RelativeLayout>

                <GridLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:useDefaultMargins="true"
                    android:rowCount="1"
                    android:columnCount="3">

                    <com.airbnb.lottie.LottieAnimationView
                        android:layout_width="100dp"
                        android:layout_height="100dp"
                        app:lottie_loop="true"
                        app:lottie_autoPlay="true"
                        app:lottie_rawRes="@raw/twitter"/>

                    <com.airbnb.lottie.LottieAnimationView
                        android:layout_width="100dp"
                        android:layout_height="100dp"
                        app:lottie_loop="true"
                        app:lottie_autoPlay="true"
                        app:lottie_rawRes="@raw/linkedin"/>

                    <com.airbnb.lottie.LottieAnimationView
                        android:layout_width="100dp"
                        android:layout_height="100dp"
                        app:lottie_loop="true"
                        app:lottie_autoPlay="true"
                        app:lottie_rawRes="@raw/whatsapp"/>

                </GridLayout>
            </LinearLayout>

        </com.google.android.material.card.MaterialCardView>


    </LinearLayout>

</ScrollView>
```
