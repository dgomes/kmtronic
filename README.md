## DEPRECATED 

This custom component has been made into an [official Home Assistant Integration](https://www.home-assistant.io/integrations/kmtronic/)


# KMtronic Integration

Integrate [KMtronic devices](https://www.kmtronic.com/) into Home Assistant. KMtronic offers a large range of IP connected relays that can be controlled over your local area network. This integration maps each of the relays as a separate device, enabling you to control various areas of your home (e.g. using each relay to control different garden sprinkler areas, or controlling electrical distribution of your house from a central board).

## Configuration

To add a KMtronice device to your installation, make sure they are connected to your home network first with a fixed IP. Next, go to **Configuration** >> **Integrations** in the UI. Click the button with `+` sign on the integrations page and from the list of integrations, select **KMtronic** and insert the IP address, Username and Password of your KMtronic device. The integration will detect how many relays your device has, and will create a switch entity for each of the relays.
