
`compile 'com.jakewharton:butterknife:8.5.1'`   
`annotationProcessor 'com.jakewharton:butterknife-compiler:8.5.1'`


`compile 'com.github.bumptech.glide:glide:3.7.0'`


`compile 'com.google.code.gson:gson:2.8.0'`

`compile 'com.github.JakeWharton:ViewPagerIndicator:2.4.1'`

`compile 'de.hdodenhof:circleimageview:2.1.0'`

`compile 'com.kyleduo.switchbutton:library:1.4.5'`



`compile 'com.mikepenz:iconics-core:2.8.3@aar'`

`compile 'com.mikepenz:fontawesome-typeface:4.7.0.0@aar'`

`compile 'com.mikepenz:ionicons-typeface:2.0.1.2@aar'`


`compile 'com.github.curioustechizen.android-ago:library:1.3.4'`


configurations.all {
    resolutionStrategy.dependencySubstitution {
        substitute module('org.apache.commons:commons-io:1.3.2') with module('commons-io:commons-io:1.3.2')
    }
}

