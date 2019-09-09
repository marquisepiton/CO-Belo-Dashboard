//Swift 



import UIKit

import WebKit



class ViewController: UIViewController, WKUIDelegate {

    

    var webview: WKWebView!



    @IBOutlet weak var beloDashboard: WKWebView!

    override func loadView() {

        let webConfiguration = WKWebViewConfiguration()

        beloDashboard = WKWebView(frame: .zero, configuration: webConfiguration)

        beloDashboard.uiDelegate = self

        view = beloDashboard

    }

    override func viewDidLoad() {

        super.viewDidLoad()

        

        let url = URL(string: "https://sites.google.com/s/1igMwdg46FFWgCpsq0HC7KugA5QGwOaj8/p/0Byi9cx7Y6Zg1ZENuM1BGSGY2dnc/edit")

        let myRequest = URLRequest(url: url!)

        beloDashboard.load(myRequest)

        

        beloDashboard.load(URLRequest(url: url!))
