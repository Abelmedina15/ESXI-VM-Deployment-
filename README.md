<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Creating a Virtual Machine in VMware Workstation</h1>
    <p>To create a virtual machine in VMware Workstation, I start by launching the software and selecting "Create a New Virtual Machine." I choose the <strong>Typical</strong> setup, select an >ISO file for the OS installation, and specify the guest operating system type.</p>
    <p>After naming the VM and selecting a storage location, I allocate disk space, configure hardware settings (RAM, CPU, and network), and finalize the setup. Once created, I power on the VM, complete the OS installation, and install VMware Tools for performance optimization.</p>
    <p>This process ensures a fully functional virtual environment tailored to my needs.</p>
  <image></image>"https://i.imghippo.com/files/ogQ3726MrQ.png"<image>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cloning a Virtual Machine in VMware Workstation</title>
</head>
<body>
    <h1>Cloning a Virtual Machine in VMware Workstation</h1>
    <p>To clone a virtual machine in VMware Workstation, first ensure the VM is powered off. Right-click the VM in the Library, select "Manage" > "Clone", and follow the cloning wizard. Choose between a Linked Clone (smaller, dependent on the original) or a Full Clone (independent, requires more storage). Name the clone, select its storage location, and complete the process. Once cloning is done, power on the new VM and adjust any necessary settings. This method allows for efficient duplication of VMs for testing, backup, or deployment.</p>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adding a Host and Migrating a VM in vSphere</title>
</head>
<body>
    <h1>How I Added a New Host to vSphere</h1>
    <p>To add a new host to vSphere, I started by logging in to the <strong>vSphere Web Client</strong> and navigating to the data center.</p>
    <ol>
        <li>I clicked <strong>"Add Host"</strong> and entered the host IP/hostname along with the root credentials.</li>
        <li>After that, I assigned a license and configured <strong>Lockdown Mode</strong> (optional).</li>
        <li>Finally, I completed the setup and ensured the host was properly added.</li>
    </ol>
    
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adding a Host and Migrating a VM in vSphere</title>
</head>
<body>
    <h1>How I Added a New Host to vSphere</h1>
    <p>To add a new host to vSphere, I started by logging in to the <strong>vSphere Web Client</strong> and navigating to the data center.</p>
    <ol>
        <li>I clicked <strong>"Add Host"</strong>, entered the host IP/hostname, and provided the root credentials.</li>
        <li>After that, I assigned a license and configured <strong>Lockdown Mode</strong> (optional).</li>
        <li>Finally, I completed the setup and ensured the host was properly added.</li>
    </ol>
    
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adding a Host and Migrating a VM in vSphere</title>
</head>
<body>
    <h1>How I Added a New Host to vSphere</h1>
    <p>To add a new host to vSphere, I started by logging in to the <strong>vSphere Web Client</strong> and navigating to the data center.</p>
    <ol>
        <li>I clicked <strong>"Add Host"</strong>, entered the host IP/hostname, and provided the root credentials.</li>
        <li>After that, I assigned a license and configured <strong>Lockdown Mode</strong> (optional).</li>
        <li>Finally, I completed the setup and ensured the host was properly added.</li>
    </ol>
    
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adding a Host and Migrating a VM in vSphere</title>
</head>
<body>
    <h1>Add a New Host to vSphere</h1>
    <p>Log in to vSphere Web Client and navigate to the data center.</p>
    <ol>
        <li>Click <strong>"Add Host"</strong>, enter the host IP/hostname and root credentials.</li>
        <li>Assign a license and configure <strong>Lockdown Mode</strong> (optional).</li>
        <li>Complete the setup.</li>
    </ol>
    
    <h1>Migrate a Virtual Machine (VM) Using vMotion</h1>
    <ol>
        <li>Right-click the VM and select <strong>"Migrate"</strong>.</li>
        <li>Choose migration type: <strong>host, storage, or both</strong>.</li>
        <li>Select the destination ESXi host and verify compatibility.</li>
        <li>Click <strong>"Finish"</strong> to complete the migration.</li>
    </ol>
    
    <h1>Post-Migration Checks</h1>
    <p>Verify the following:</p>
    <ul>
        <li>VM functionality</li>
        <li>Network connections</li>
        <li>Overall performance</li>
    </ul>
    <p>This ensures smooth host integration and VM migration in VMware.</p>
</body>
</html>
