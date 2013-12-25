############################
Recommendations
############################

.. function:: get_last_updated_time_for_recommendations(self, marketplaceid)

    Checks whether there are active recommendations for each category for the given marketplace, and if there are, returns the time when recommendations were last updated for each category.

    :param string marketplaceid: Define the specific Marketplace ID
    :returns: something from amazon


.. function:: list_recommendations(self, marketplaceid, recommendationcategory=None)

    Returns your active recommendations for a specific category or for all categories for a specific marketplace.

    :param string marketplaceid: Define the specific Marketplace ID
    :param string recommendationcategory:
    :returns: something from amazon


.. function:: list_recommendations_by_next_token(self, token):

    Returns the next page of recommendations using the NextToken parameter.

    :param string token:
    :returns: something from amazon