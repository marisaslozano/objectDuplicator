Object Duplicator is a robust UI made with PyMel. The UI dupliactes objects on a given surface, where the user can customize scale, rotation, and import custom models.  

Put objectDuplicator.py in your Maya scripts directory or add the folder with myModule.py to your python path.
Type this into the Script Editor:
'''python
# to add path
import sys 
sys.path.append( 'C:\Users\Marisa\Documents/objectDuplicator' )

# otherwise, run this
import objectDuplicator as ob
reload(ob)
ob.run()
'''