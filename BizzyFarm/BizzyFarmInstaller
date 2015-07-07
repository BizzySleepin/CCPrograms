if not fs.exists("BizzyFarm") then
        fs.makeDir("BizzyFarm")
        print("Config directory created")
        sleep(.5)
end
 
term.clear()
print("Welcome to the BizzyFarm Installer!")
print("\nPress H to install the Harvester program")
print("Press P to install Planter program")
print("Press C to install the Control Panel program")
listen = true
while listen == true do
  local sEvent, param = os.pullEvent("key")
  if sEvent == "key" then
    if param == 25 then
      term.clear()
      print("Planter Program Selected!")
      shell.run("delete startup")
      shell.run("delete BizzyFarm/Settings")
      shell.run("delete BizzyFarm/StartPos")
      shell.run("pastebin get JdgyLn4j startup")
      print("Running Planter program in 2 seconds")
      sleep(2)
      shell.run("startup")
    end
    if param == 35 then
      term.clear()
      print("Harvester Program Selected!")
      shell.run("delete startup")
      shell.run("delete BizzyFarm/Settings")
      shell.run("delete BizzyFarm/StartPos")
      shell.run("pastebin get 6t0mCXLs startup")
      print("Running Harvester program in 2 seconds")
      sleep(2)
      shell.run("startup")
    end
    if param == 46 then
      term.clear()
      print("Control Panel Program Selected!")
      shell.run("delete startup")
      shell.run("delete BizzyFarm/Settings")
      shell.run("delete BizzyFarm/StartPos")
      shell.run("pastebin get gKEFqnxX startup")
      print("Running Control Panel program in 2 seconds")
      sleep(2)
      shell.run("startup")
    end
    listen = false
  end
end
