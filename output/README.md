Your output files must be delivered to this folder in order to be saved as output artifacts by the GitHub action.  For example, you should specify a recorder as follows to generate a CSV file in the output folder:

~~~
object recorder
{
  file "output/test.csv";
  // ...
}
~~~
