# NIST chemistry webbook wrapper
Easy to use wrapper for NIST chemistry webbook database. Allows to get required physical properties from NIST chemistry database without opening website in browser and in much faster and convenient than manual searching.  

source: http://webbook.nist.gov/chemistry/fluid/

### Requirements:
Pandas is required:

You can simply install it with
> ` pip unstall pandas `

Or from file *requirements.txt* , with command:
> ` pip install -r requirements.txt `

### Default requests:

Check full descriptions of available units and substance in file [default_request.md](https://github.com/subpath/NIST_chemistry_webbook_wrapper/blob/master/default_request.md)


### Example of usage:

>  `data = getNIST(fluid_id = Fluids_ID['argon'], Temp = 30, Plow = 140, Phigh= 200, deltaP = 10, TypeOfData ='IsoTherm')`

data will be return as pandas [DataFrame](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html) , and then can easily managed, and exported in [different files type](http://pandas.pydata.org/pandas-docs/stable/io.html).


[See for more examples](https://github.com/subpath/NIST_chemistry_webbook_wrapper/tree/master/examples).


##### Author:                                                                                                                                               
> Alexander Osipenko,     
> e-mail: subpath@ya.ru



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/subpath/nist_chemistry_webbook_wrapper/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

