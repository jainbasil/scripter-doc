Add a menu to Scribus MenuBar
==============================

The following script will add a new menu to Scribus MainWindow menubar.::

		# -*- coding: utf-8 -*-
		from __future__ import with_statement
		from PyQt4.QtGui import qApp, QMenu, QAction

		def add_test():
		    menuBar = Scripter.dialogs.mainWindow.qt.menuBar()	
		    item_action = None
		    for action in menuBar.actions():
		        if action.text() == "&View":
		            item_action = action
		    menuBar.insertMenu(item_action, QMenu("&TTest", menuBar))
		            
		def run(): 
		    add_test()

		run()
