- š Hi, Iām @GjonW
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
GjonW/GjonW is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import com.rollbar.android.Rollbar

public class MainActivity extends AppCompatActivity {

  @Override
  protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    Rollbar.init(this);
    Rollbar.instance().error(new Exception("This is a test error")); //remove this after initial testing
  }
