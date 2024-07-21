---
title: Request brochure
layout: base.njk
---

<form method="post" name="requestbrochure" netlify>
    <label>Name: <input type="text" required /></label>
    <label>Phone: <input type="text" required /></label>
    <label>Mailing Address: <br /><textarea cols="50" rows="6"></textarea></label>
    <label>Type of Boat/Yacht Interested in Chartering:
    <select>
        <option value="Any" default>Any</option>
        <option value="Motoryacht">Motoryacht</option>
        <option value="Motorsailer">Motorsailer</option>
        <option value="Sportfish">Sportfish</option>
        <option value="Sailboat">Sailboat</option>
        <option value="Trawler">Trawler</option>
        <option value="Dayboat">Dayboat</option>
    </select></label>
    <label>Length of Boat Desired: <input type="text" size="5"/> fts.</label>
    <label>Number of Guests: <input type="text" size="5"/></label>
    <label>Departure, Stops, Destinations, etc:<br /><textarea cols="50" rows="6"></textarea></label>
    <label>
    <input type="submit" /> 
    <input type="reset" /></label>
</form>
