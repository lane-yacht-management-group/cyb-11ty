---
title: Request brochure
layout: base.njk
---

<form method="post" name="requestbrochure" netlify>
    <label>Name: <input name="name" type="text" required /></label>
    <label>Phone: <input name="phone" type="text" required /></label>
    <label>Mailing Address: <br /><textarea name="address" cols="50" rows="6"></textarea></label>
    <label>Type of Boat/Yacht Interested in Chartering:
    <select name="type_of_boat" class="form-control--inline" >
        <option value="Any" default>Any</option>
        <option value="Motoryacht">Motoryacht</option>
        <option value="Motorsailer">Motorsailer</option>
        <option value="Sportfish">Sportfish</option>
        <option value="Sailboat">Sailboat</option>
        <option value="Trawler">Trawler</option>
        <option value="Dayboat">Dayboat</option>
    </select></label>
    <label>Length of Boat Desired: <input class="form-control--inline" name="length" type="text" size="5"/> fts.</label>
    <label>Number of Guests: <input name="number_of_guests" class="form-control--inline"  type="text" size="5"/></label>
    <label>Departure, Stops, Destinations, etc:<br /><textarea name="departure" cols="50" rows="6"></textarea></label>
    <label>
    <input type="submit" /> 
    <input type="reset" /></label>
</form>
