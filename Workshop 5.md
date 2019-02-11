Segues
**What is a segue**
transition between two view controllers

**What is a segue identifier?**
Name of segue 
Name = string

**How do you create segue from a button?**
ctrl drag from button to new view controller

**How do you create from a view controller without a button?**
Editor-Navigation Controller

Ctrl + drag view controller to new VC

extension ViewController: MKMapViewDelegate {
    func mapView(_ mapView: MKMapView, didSelect view: MKAnnotationView) {
        performSegue(withIdentifier: "Next", sender: nil)
    }
    
**What is the method to perfrom a segue called and what argument does it take?**

**What method is called immediatly before a segue is performed?**

**How do you assign a new view controller class?**
selecting the second view controller - top right - little picture frame and type in new viewcontroller name

**How do you pass data between two view controllers? (this will need a few sentances to explain)**

**You dont link a segue "backwards", why?**
Becasue it stacks the view controllers on top of eachothe and this will cause the app to run out of memory and crash
