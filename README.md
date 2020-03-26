# DesignPatterns
Afternoon Project:

1. The singleton design pattern - example: let sharedURLSession = URLSession.shared

2. One ex. of a UIKit class that uses the singleton pattern is StoreKit Framekit.

3. Facade example - adding var albumController = AlbumController() into 

class AlbumsTableViewController: UITableViewController {
    var albumController = AlbumController()
  }
  
 So you dont have to rewrite all of AlbumController code. but just adding that smaller code, its cleaner.
 

