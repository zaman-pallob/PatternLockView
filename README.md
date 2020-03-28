# Pattern Lock View

<img src="https://github.com/zaman-pallob/patternlockview/blob/screenshot/banner.png" alt="drawing" width="1000" height="400" />



# Dependency  
###### build.gradle (Project)
                 allprojects {
                      repositories {
                                  google()
                                  jcenter()
                                  maven { url 'https://jitpack.io' }
        
                                   }
                            }
###### build.gradle (app)
              dependencies {  
                             implementation 'com.github.zaman-pallob:patternlockview:1.0.0'
                            }
                            
# Usage

##### Place the view in your XML layout file. 

                                    <com.pallob.lib.PatternLockView
                                        android:id="@+id/pattern_lock_view"
                                        android:layout_width="match_parent"
                                        android:layout_height="wrap_content"
                                        app:lineColor="@color/green_dark"
                                        app:normalColor="@color/white"
                                        app:highlightedColor="@color/green_dark"
                                        app:lockSize="3"
                                      />

 ##### Implements the view in code as follows
                                   
                                 
                                   
                                   PatternLockView patternLockView=findViewById(R.id.pattern_lock_view);

                                   patternLockView.setListener(new PatternLockView.Listenser() {
                                   @Override
                                   public void onFinish(String pattern) {
                                              
                                        } 
                                    });
                                    
                                    
                                    
                              
 
 
 # License
                                    
    MIT License

    Copyright (c) 2020 Atikur Zaman Pallob

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.                
                                    
                                    
                                    
                                    
                                      
                                      
                                      
  
