# RecycleViewDemo

#Using a RecyclerView has the following key steps:

    1)Add RecyclerView and CardView AndroidX library to the Gradle build file
    2)Define a ListItem class to use as the data source
    3)Add a RecyclerView to your activity to display the items
    4)Create a custom list_items layout XML file to visualize the item
    5)Create a RecyclerView.Adapter and ViewHolder to render the item
    6)Bind the adapter to the data source to populate the RecyclerView
    7)OnClick On RecycleViewItem
    
 # Make sure the RecyclerView AndroidX library is listed as a dependency in your app/build.gradle:

dependencies {
    ...
    implementation 'androidx.cardview:cardview:1.0.0'
    implementation 'androidx.recyclerview:recyclerview:1.1.0-rc01'
}
